# Vendure plugin Seller Verification

This is an open-source plugin that is open to the community to use in any capacity.

Plugin allows superadmin to enable/disable sellers. This can be used to verify sellers if sellers need to be verified in some capacity before being able to post items for sale.

A Seller that is not verified will not be able to create/modify products. A seller that is verified will be able to create/modify products.

This plugin is a work-in-progress and will include additional features in the near future.

## Testing

1. Run `yarn test` to run the e2e test.
2. Don't forget to implement your own!

## Publishing to NPM

1. Make sure you are [logged in to NPM](https://docs.npmjs.com/cli/v9/commands/npm-login)
2. `yarn build`
3. `yarn publish`

That's it!

(Maybe share your accomplishments in the [Vendure slack](https://join.slack.com/t/vendure-ecommerce/shared_invite/zt-1exzio25w-vjL5TYkyJZjK52d6jkOsIA)?

## Next steps

1. Check out [the docs](https://www.vendure.io/docs/plugins/) to see the possibilities of a plugin
2. Check out [GraphQL codegen](https://the-guild.dev/graphql/codegen) to generate Typescript types for your custom GraphQL types
