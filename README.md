# OID registry

Ubirch owns the Private Enterprise Number 54021, giving it a unique sub‐tree in the global OID tree (`1.3.6.1.4.1.54021`).

To ensure unique identifiers for every object, they should follow the form outlined in this document.

The first level below the PEN defines the scope:

- `1.3.6.1.4.1.54021.0` to be used for documents,
- `1.3.6.1.4.1.54021.1` to be used for products,
- `1.3.6.1.4.1.54021.2` to be used for projects, and
- `1.3.6.1.4.1.54021.255` to be used for experimentation.

All other numbers immediately below the PEN are reserved for future use.

## Documents

Documents may be assigned a unique number below the `1.3.6.1.4.1.54021.0` tree.

Assignments must be recorded in the `document.tsv` file in the repository root.

## Product

Products may be assigned a unique number below the `1.3.6.1.4.1.54021.1` tree.

Assignments must be recorded in the `product.tsv` file in the repository root.

### Service

Numbers within a product sub‐tree should be separated by service.

Services must be recorded in the `service.tsv` file in the repository root.

## Project

Projects may be assigned a unique number below the `1.3.6.1.4.1.54021.2` tree.

Assignments must be recorded in the `project.tsv` file in the repository root.

## Experimentation

The `1.3.6.1.4.1.54021.255` tree may be used freely for experimentation.
