# Personal Best Localisation

This is the community language repository for [Personal Best](https://codakuma.com/personal-best).

If you'd like to see Personal Best localised to a specific language, please submit a pull request to this repository.

I'm extremely grateful for **all** submitted localisations, even incomplete ones.

## Structure

Languages are structured in folders like so:

```
en.lproj/Localizable.strings
```

Where en is replaced by the [ISO 639-1 two-letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), and the `Localizable.strings` file is structured as per the English (en) version.

## Localization

Strings are denoted as `"KEY"` = `"value"`, where the keys remain the same across all languages, and the values are localized. There must be a `;` at the end of each line.

`"SEARCH_PLACEHOLDER" = "Search";`

### Workout types

Localised workout types can be retrieved from watchOS by starting a workout, going to the A-Z list and matching up the icons with the string provided.

This is very slow, dull work and if you don't wish to localise that part, leave it out of the pull request and I can do it.

## Inspiration

This project is inspired and is pretty much an exact copy of Steve Troughton-Smith's [broadcast-localization](https://github.com/steventroughtonsmith/broadcasts-localization) repo.

## Credit

If you would like to be credited for your work inside Personal Best, add a comment block to the top of the `Localizable.strings`.