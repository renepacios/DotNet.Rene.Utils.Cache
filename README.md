
# DotNet Rene Utils Cache

## Overview

DotNet Rene Utils Cache is a utility service library designed to implement a double-layer cache system. It stores data in both a memory cache and a distributed system cache. 

The library provides too,  a service that runs in the background to refresh cache entries and more.

## Features

- **Memory Cache**: Stores frequently accessed data in memory for quick retrieval.
- **Distributed Cache**: Stores data in a distributed system for scalability and fault tolerance.
- **Cache Retrieval**: 
  - First, attempts to read data from the memory cache.
  - If the data is not found in the memory cache, it tries to retrieve it from the distributed cache.
  - If the data is not found in the distributed cache, it reads from the original source and stores the data in both caches.
- **Background Service**: A service that runs in the background to refresh cache entries.

## Installation

To install the library, you can use NuGet Package Manager in Visual Studio:


## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Code of conduct
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please open an issue on GitHub.

---

Thank you for using DotNet Rene Utils Cache!