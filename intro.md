# Sparse Matrices with Linked Lists

An implementation of a Sparse Matrix class using Linked List for CSC 212's final project
Our representation included implementing a Sparse MAtrix by Lists of Linked Lists
Each node looks like:
| int row  | Node* next in row --> |
|----------|-----------------------|
| int col  | Node* next in col  v  |
| int data |                       |

While the Matrix class holds two array of Node* that hold the first of the next node in col and the other holding the first of node next in row (poor explanation but picture of this jupyter book shows how it should look):

## Setup

This section covers the setup process.

### Setup Document

See [Setup Document](setup_doc.md) for detailed instructions on setting up the project.

## Sample Matrices

This section covers sample matrices.

### Matrices Document

See [Matrices Document](matrices_doc.md) for information about sample matrices.

## Source Files

This section covers the source files.

### Matrix Header

See [Matrix Header](headers/Matrix_Header.md) for the header file of the Matrix class.

### Matrix Source

See [Matrix Source](source/Matrix_Source.md) for the source file of the Matrix class.

### Node Header

See [Node Header](headers/Node_Header.md) for the header file of the Node class.

### Node Source

See [Node Source](source/Node_Source.md) for the source file of the Node class.

### Main

See [Main](main.md) for the main source file of your project.

## More Info

This section provides additional information.

### Report

See [Report](more_info/report.md) for detailed information and reports.
