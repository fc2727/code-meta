# Code Meta

[![Release](https://img.shields.io/badge/Release-v1.0.0-blue.svg)](https://github.com/YuetChan/code-meta/releases/tag/v1.0.0)
[![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)](https://github.com/YuetChan/code-meta)
[![Issue](https://img.shields.io/github/issues/YuetChan/code-meta)](https://github.com/YuetChan/code-meta/issues)
[![License](https://img.shields.io/badge/License-GPL-yellow.svg)](https://github.com/YuetChan/code-meta/blob/main/LICENSE)

Code Meta is a note-taking app that allows developers to easily manage and edit notes associated with files in a software project.

![CodeMetaScreenshot](https://i.ibb.co/cJ0RBQ3/Screenshot-from-2023-04-13-00-32-03.png)

## Dependencies

The following dependencies are required to run the Project Name application:

- Python 3.8 +

## Installation

1. Clone the Code Meta repository: `git clone https://github.com/YuetChan/code-meta.git`
2. Change to the code-meta directory: `cd /path/to/code-meta`
3. Make the build.sh script executable: `chmod +x ./build.sh`
4. Code Meta icon should show up on show applications/application menu

## Usage

- Open existing projects: Users can open an existing project by reading the s_config.json file for the project name and project ID.
- Create new projects: Users can create new projects, which will generate a s_config.json file that contains Project name and Project ID.
- File tree and text editor: Once a project is opened or created, users can view a file tree and a text editor for editing notes associated with files.
- Dangling file searcher: The application provides a search bar and a file list that displays files with dangling notes, which are notes associated with files that are not present in the file tree.
- Auto deletion: When users empty dangling notes, it will remove the associated file from the file list.

### Video on usage

[![](https://i.ibb.co/BV9nDvF/643a1c3f79c3c-fbutube-code-meta-thumbnail.png)](https://www.youtube.com/watch?v=dZb2pFhr-NA)


## License

This project is licensed under the GPL License - see the [LICENSE](https://github.com/YuetChan/code-meta/blob/master/LICENSE)
 file for details.

## Contact Information

For any questions or inquiries, please contact Yuet Chan at yuetcheukchan@gmail.com.
