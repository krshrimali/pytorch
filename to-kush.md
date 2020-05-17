This branch was made in order to add support for Long types to trigonometric functions.

Even though passing Long tensors doesn't sound any obvious, but some people might just do it. Instead of returning an error, we should promote them to Floating types.
