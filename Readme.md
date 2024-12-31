# Timezone CLI

## Overview

Timezone CLI is a command-line tool built with Go and Cobra that allows you to quickly retrieve the current time in any specified timezone.

## Features

- Get current time in a specific timezone
- Optional date formatting
- Simple and intuitive CLI interface

## Prerequisites

- Go 1.16+
- Cobra CLI library

## Installation

```bash
go install github.com/meeklife/module
```

## Usage

### Basic Usage

```bash
module timezone GMT
```

```bash
module timezone Africa/Accra
```

### Date Formatting

```bash
module timezone GMT --date 01/01/2000
```
