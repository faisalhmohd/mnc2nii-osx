# mnc2nii for OSX

Convert a MINC format file to a NIfTI-1 or Analyze format file on OSX.

## Usage

#### Via Git

```sh
$ git clone https://github.com/faisalmohd/mnc2nii-osx.git
$ ./mnc2nii [<options>] <infile.mnc> <outfile.mnc>
```

#### Manual

Download [package](https://github.com/faisalmohd/mnc2nii-osx/archive/master.zip) and extract. On terminal, open the extracted folder and run:

```sh
$ ./mnc2nii [<options>] <infile.mnc> <outfile.mnc>
```

## Options

Available as per [this](http://manpages.ubuntu.com/manpages/dapper/man1/mnc2nii.1.html) Manpage .

## Description

The mnc2nii command is used to convert  MINC  format  files  to  either
NIfTI-1  or  Analyze  format.   The NIfTI-1 format was developed by the
members of the Neuroinformatics  Technology  Initiative’s  Data  Format
Working  Group  (DFWG).   The  NIfTI-1  format  is  based upon the Mayo
Clinic’s Analyze 7.5 format.

The name of the program is derived from the  common  filename  suffixes
used for NIfTI-1 and MINC files.  NIfTI-1 defines two possible formats,
a "header plus raw image" 2-file format, and a single-file format  that
includes  both  header information and the image data.  As with Analyze
7.5, the 2-file format consists of one file with the suffix ".hdr"  and
another file with the extension ".img".  In NIfTI-1 single-file format,
the two files may be combined into a single file with a ".nii" filename
suffix.

In  addition  to the NIfTI-1 formats, mnc2nii can convert MINC files to
the Analyze 7.5 format.

## [Original Repo](https://github.com/BIC-MNI/minc-tools)

License
----

ISC
