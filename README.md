# Audio Volume Modifier

## Description
This project is an audio volume modifier written in C. It allows users to modify the volume of a .wav audio file by a specified factor. The program reads the input .wav file, adjusts the volume of each audio sample, and writes the modified audio to an output .wav file.

## Features
- Modify the volume of a .wav audio file by a specified factor
- Supports 16-bit PCM .wav files
- Preserves the original .wav file header

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/volume-modifier.git
   ```
2. Navigate to the project directory:
   ```bash
   cd volume
   ```
3. Compile the code:
   ```bash
   make volume
   ```

## Usage
1. Run the application:
   ```bash
   ./volume input.wav output.wav factor
   ```
   Replace `input.wav` with the path to the input .wav file, `output.wav` with the path to the output .wav file, and `factor` with the volume scaling factor (e.g., 0.5 to halve the volume, 2.0 to double the volume).

## Example
```bash
$ ./volume input.wav output.wav 1.5
```

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is not licensed under any License currently. 
