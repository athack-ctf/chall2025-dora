Dora The Explorer: Quest for the Quantum Treasure

> The challenge is a storytelling-based staganography puzzle. It introduces participants to various staganographic techniques in a narrative that follows an AI version of Dora as she searches for the coordinates of a lost civilization.

## Type

- [X] **OFF**line
- [ ] **ON**line

## Designer

- Little Squid

## Description

Participants will be given an image. In the image, there is a zip file. In the zip file, there are two audio files, one of which contains a hint and the other contains a Ceaser cipher of the flag which you can see through spectogram. 

Educational Goals:
(1) Participants will learn about image and audio steganography through techniques such as file extraction and spectogram analysis.
(2) By encountering Caesar cipher text, partipants will develop foundational cryptographic decoding skills.

Skills Test:
(1) Participants will gain experience with Binwalk tool for extracting hidden files from the given image.
(2) Using tools like Audacity, Sonic Visualiser, participants will learn to interpret spectogram data.
(3) Basic Caesar cipher skills are tested to decode the extracted information.
(4) Each hint directs participants to new tools and decoding strategies.

**IMPORTANT:** This description will **NOT** be shared with participants.

## Category

- `stegano`
---

# Project Structure

## 1. HACKME.md

- **[HACKME.md](HACKME.md)**: A teaser or description of the challenge to be shared with participants (in CTFd).

## 2. Source Code

- **[source/README.md](source/README.md)**: Sufficient instructions for building your offline artifacts from source
  code. If your project includes multiple subprojects, please consult us (Anis and Hugo).
- **[source/*](source/)**: Your source code.`

## 3. Offline Artifacts

- **[offline-artifacts/*](offline-artifacts/)**: All files (properly named) intended for local download by
  participants (e.g., a binary executable for reverse engineering, a custom-encoded image, etc.). For large files (
  exceeding 100 MB), please consult us (Anis and Hugo).

## 4. Solution

- **[solution/README.md](solution/README.md)**: A detailed writeup of the working solution.
- **[solution/FLAGS.md](solution/FLAGS.md)**: A single markdown file listing all (up-to-date) flags.
- **[solution/*](solution/)**: Any additional files or code necessary for constructing a reproducible solution for the
  challenge (e.g., `PoC.py`, `requirement.txt`, etc.). 
