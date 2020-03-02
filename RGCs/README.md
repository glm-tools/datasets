# Dataset for GLM for Spike Trains Prediction in Primate Retinal Ganglion Cells

The dataset contains spike responses from 2 ON and 2 OFF parasol
retinal ganglion cells (RGCs) in primate retina, stimulated with
full-field _binary white noise_. Two experiment performed consisted of a
long (20-minute) binary stochastic (non-repeating) stimulus
which can be used for computing the spike-triggered average
(or characterizing some other model of the response).

## Data structure

The dataset is in JSON format with the follows keys

- `stim`: contains a list of binary stochastic stimulation where the value is its stimulation intensity
- `stim_times`: time of the stimulation
- `spike_times`: recorded time of the spikes
  - `cell_0`: OFF cell
  - `cell_1`: OFF cell
  - `cell_2`: ON cell
  - `cell_3`: ON cell

## Dataset description

These data were collected by Valerie Uzzell in the lab of
E.J. Chichilnisky at the Salk Institute. For full information, please see
[Uzzell et al., J Neurophys, 2004](http://med.stanford.edu/content/dam/sm/chichilnisky/documents/publications/Uzzell2004.pdf),
or [Pillow et al., J Neurosci, 2005](https://www.jneurosci.org/content/25/47/11003).

## License

This dataset (RGC spikes data) is granted by original authors (E.J. Chichilnisky and Jonathan Pillow).
The dataset ramains a property of the original authors.
Its use and transfer outside tutorial, e.g. for research purposes,
is prohibited without written consent to the original authors.

If you reference this dataset in your publications, please:
    1) acknowledge its authors: E.J. Chichilnisky and Jonathan Pillow
    2) cite thier publications as indicated above

If you want to use it beyond the educational purposes or have further questions, please contact
Jonathan Pillow (pillow@princeton.edu).
