# Definitions

<a id="drhook-c"></a>

## \_DRHOOK_C_

### Value

`1`

### Purpose

Never used within `drhook.c`

### Preprocessor Guards

None

<!-- ############################################### -->

<a id="drhook-file"></a>

## \_DRHOOK_FILE_

### Value

`drhook.c`

### Purpose

Used within error handling to specify the source file where it occurred.

### Preprocessor Guards

None

<!-- ############################################### -->

<a id="gnu-source"></a>

## \_GNU_SOURCE

### Value

No value defined

### Purpose

Never used within `drhook.c`.

### Preprocessor Guards

None

<!-- ############################################### -->

<a id="host-name-max"></a>

## HOST_NAME_MAX

### Value

`_POSIX_HOST_NAME_MAX`

### Purpose

Used to set the max size of char arrays for node HOSTNAME.

### Preprocessor Guards

`!defined(HOST_NAME_MAX) && defined(_POSIX_HOST_NAME_MAX)`

<!-- ############################################### -->

<a id="id16"></a>

## HOST_NAME_MAX

### Value

`_SC_HOST_NAME_MAX`

### Purpose

Used to set the max size of char arrays for node HOSTNAME.

### Preprocessor Guards

`!defined(HOST_NAME_MAX) && defined(_SC_HOST_NAME_MAX)`

<!-- ############################################### -->

<a id="ec-host-name-max"></a>

## EC_HOST_NAME_MAX

### Value

`HOST_NAME_MAX`

### Purpose

Used to set the max size of char arrays for node HOSTNAME.

### Preprocessor Guards

`defined(HOST_NAME_MAX)`

<!-- ############################################### -->

<a id="id25"></a>

## EC_HOST_NAME_MAX

### Value

`512`

### Purpose

Used to set the max size of char arrays for node HOSTNAME.

### Preprocessor Guards

`!defined(HOST_NAME_MAX)`
