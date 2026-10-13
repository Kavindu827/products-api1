# Tutorial 2 observations

With public fields, the product response included id, name and price.

After making all fields private without getters, I observed: [write what you actually saw here].

Adding the public getters restored all three fields.

Removing getName() removed name from the response. Restoring it brought name back.

For a class with many fields, I would compare the response with the expected fields instead of checking only the status code.