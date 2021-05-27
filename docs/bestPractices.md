# Custom Element Best Practices

## Reflect properties to attributes if that attribute is used as a styling hook

https://github.com/AlaskaAirlines/auro-badge/pull/11

If a consumer sets the property, the correct styles still apply.

Open-WC recommends avoiding reflecting properties unless necessary: https://open-wc.org/guides/knowledge/attributes-and-properties/#attribute-and-property-reflection

Google recommends reflecting: https://developers.google.com/web/fundamentals/web-components/best-practices#aim-to-keep-primitive-data-attributes-and-properties-in-sync,-reflecting-from-property-to-attribute,-and-vice-versa.

## If you query the children of a custom element, react to slot changes

https://github.com/AlaskaAirlines/auro-accordion/pull/21


## Other best practice docs
- https://developers.google.com/web/fundamentals/web-components/best-practices