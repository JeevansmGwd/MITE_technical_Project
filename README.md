
# File Editing Program README

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Compilation](#compilation)
  - [Running the Program](#running-the-program)
- [Usage](#usage)
  - [Menu Options](#menu-options)
    - [1. View File Contents](#1-view-file-contents)
    - [2. Edit File (Insert)](#2-edit-file-insert)
    - [3. Edit File (Delete)](#3-edit-file-delete)
    - [4. Find and Replace](#4-find-and-replace)
    - [5. Save and Exit](#5-save-and-exit)
-
## Introduction

This program is a versatile text file editing tool written in C. It empowers users to perform various file manipulation tasks, such as viewing file contents, inserting text at specific positions, deleting text, and finding and replacing text within the file. The program provides an interactive command-line interface that allows users to choose operations from a menu.

## Features

- View the complete contents of a text file.
- Insert custom text at a specified position.
- Delete a specified amount of text from a given position.
- Find and replace specific text occurrences within the file.
- Save changes made during editing and exit the program.

## Getting Started

### Prerequisites

To compile and run the program, you need:

- A C compiler (e.g., GCC) installed on your system.

### Compilation

1. Open your terminal.

2. Navigate to the directory containing the source code file (`file_editor.c`).

3. Compile the code using the following command:
   
   
   gcc -o file_editor file_editor.c


### Running the Program

1. After compilation, run the program using this command:
   
   
   ./file_editor


## Usage

### Menu Options

The program presents users with a menu-driven interface that guides them through various file editing operations.

#### 1. View File Contents

Select this option to display the entire contents of the chosen text file.

#### 2. Edit File (Insert)

Choose this option to insert custom text at a specified position within the file. You'll need to provide:
- The position where the text should be inserted.
- The text to be inserted.

#### 3. Edit File (Delete)

Opt for this option to delete a specified amount of text from a chosen position in the file. You'll need to provide:
- The position from which the deletion should start.
- The length (number of characters) to be deleted.

#### 4. Find and Replace

Select this option to find specific text within the file and replace all occurrences with custom replacement text. You'll need to provide:
- The text to be found.
- The replacement text.

#### 5. Save and Exit

Use this option to save any changes made during editing and exit the program.


