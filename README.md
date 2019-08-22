# Replicate Paragraphs

Replicate Paragraphs extends the Replicate module to manage the cloning of
paragraphs_item entities and fields.

## Installation

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Dependencies

- Replicate
- Paragraphs

## Configuration and Usage

When you clone an entity (node, taxonomy term, ...) containing a 
paragraphs reference, the paragraphs items are not duplicated, 
and the cloned entity still references the same paragraphs than 
the original entity.
This poses great issues as any modification on the paragraphs will impact 
all the duplicated entities.

Replicate Paragraphs corrects that behavior and implements a clean
duplication of paragraphs.
The replication is recursive, ie. will work on paragraphs containing
paragraphs and so on.

More details may be found (or added) in the [Wiki](https://github.com/backdrop-contrib/replicate_paragraphs/issues).

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/replicate_paragraphs/issues).

## Current Maintainers

- [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org) 

## Credits

- Ported to Backdrop by [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org)
- Maintained for Drupal by [fabianderijk](https://www.drupal.org/u/fabianderijk), [seanB](https://www.drupal.org/u/seanB), and [reinier-V](https://www.drupal.org/u/reinier-V).
- This module was based on the [Replicate field collection](https://drupal.org/project/replicate_field_collection) module! Thank you [jgalleta](https://www.drupal.org/u/jgalletta)!
- Thanks also to [Vincent Bouchet](https://www.drupal.org/u/vbouchet) and everyone involved in [this discussion](https://drupal.org/node/1233256).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
