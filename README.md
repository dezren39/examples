# Motion Canvas Examples

## How to run

This project uses Git Large File Storage for storing non-textual assets like
images and audio. Make sure that you have [Git LFS][git-lfs] installed and that
you cloned the project using git. **Downloading it as a ZIP archive will result
in said assets missing.**

1. Clone the project
2. Install all the necessary packages in the root of the project:
   ```shell
   npm install
   ```
3. Run one of the available examples, for instance:
   ```shell
   npm run deferred-lighting
   ```
   Take a look at [`package.json`](./package.json) for the list of available
   examples.

For the sake of size, the audio in these examples uses the `mp3` format. This
may cause the audio to be slightly desynchronized with the animation (The
displayed waveform is remains correct). `wav` files don't have this issue and
are the recommended format when working with Motion Canvas.

[git-lfs]: https://git-lfs.github.com/
