# JILL - Julia Installer 4 Linux - Light

Simply install latest [Julia](https://julialang.org)
[![Build
Status](https://travis-ci.org/abelsiqueira/jill.svg?branch=master)](https://travis-ci.org/abelsiqueira/jill)

Last tested version: ![Julia 0.6.2](https://img.shields.io/badge/julia-0.6.2-3a5fcc.svg?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAB+FBMVEUAAAA3lyU3liQ4mCY4mCY3lyU4lyY1liM3mCUskhlSpkIvkx0zlSEeigo5mSc8mio0liKPxYQ/nC5NozxQpUBHoDY3lyQ5mCc3lyY6mSg3lyVPpD9frVBgrVFZqUpEnjNgrVE3lyU8mio8mipWqEZhrVJgrVFfrE9JoTkAVAA3lyXJOjPMPjNZhCowmiNOoz1erE9grVFYqUhCnjFmk2KFYpqUV7KTWLDKOjK8CADORj7GJx3SJyVAmCtKojpOoz1DnzFVeVWVSLj///+UV7GVWbK8GBjPTEPMQTjPTUXQUkrQSEGZUycXmg+WXbKfZ7qgarqbYraSVLCUV7HLPDTKNy7QUEjUYVrVY1zTXFXPRz2UVLmha7upeMCqecGlcb6aYLWfaLrLPjXLPjXSWFDVZF3VY1zVYlvRTkSaWKqlcr6qesGqecGpd8CdZbjo2+7LPTTKOS/QUUnVYlvVY1zUXVbPSD6TV7OibLuqecGqecGmc76aYbaibLvKOC/SWlPMQjrQUEjRVEzPS0PLPDL7WROZX7WgarqibLucY7eTVrCVWLLLOzLGLCLQT0bIMynKOC7FJx3MPjV/Vc+odsCRUa+SVLCDPaWVWLKWWrLJOzPHOTLKPDPLPDPLOzLLPDOUV6+UV7CVWLKVWLKUV7GUWLGPUqv///8iGqajAAAAp3RSTlMAAAAAAAAAAAAAABAZBAAAAABOx9uVFQAAAB/Y////eQAAADv0////pgEAAAAAGtD///9uAAAAAAAAAAcOQbPLfxgNAAAAAAA5sMyGGg1Ht8p6CwAAFMf///94H9j///xiAAAw7////65K+f///5gAABjQ////gibg////bAAAAEfD3JwaAFfK2o0RAAAAAA4aBQAAABEZAwAAAAAAAAAAAAAAAAAAAIvMfRYAAAA6SURBVAjXtcexEUBAFAXAfTM/IDH6uAbUqkItyAQYR26zDeS0UxieBvPVbArjXd9GS295raa/Gmu/A7zfBRgv03cCAAAAAElFTkSuQmCC)

On Linux, the best way to install Julia is to use the Generic Linux
Binaries. And while **all Linux users** love manually downloading,
unpacking, and linking their software, this script does it for you.

Simply run

    bash -ci "$(curl -fsSL https://raw.githubusercontent.com/abelsiqueira/jill/master/jill.sh)"

If you want to avoid using sudo, create a folder, add it to your PATH
and then issue

    JULIA_INSTALL=yourfolder bash -ci "$(curl -fsSL https://raw.githubusercontent.com/abelsiqueira/jill/master/jill.sh)"

## LICENSE

This script is licensed under the GNU GPLv3 (see
[LICENSE.md](LICENSE.md)). This dosn't affect your Julia usage at all.
