# MP3 Meta Data Reader
A C++ header-only class for reading basic metadata from MP3 files, currently supporting both ID3v1 and ID3v2 tags. This class extracts information such as the title, artist, album, and year from the MP3 file metadata.

# Features:
* Header-only
* Currently supports ID3v1 and ID3v2 tags
  
# Requirements
* C++11 or later.

# To-Do

- **UTF-16 and UTF-8 Support**
  - Add support for more advanced UTF-16 and UTF-8 decoding to improve compatibility with various ID3v2 frames.

- **Extended ID3 Tag Parsing**
  - Expand the functionality to parse additional ID3v2 frames, such as:
    - **Album Art**: Parse APIC (Attached Picture) frames to extract album artwork.
    - **Genre**: Support parsing genre information in ID3 tags.
    - **Comments**: Retrieve user comments stored in comment frames.
    - **Track Number**: Extract track numbers and other metadata like disc numbers if available.

