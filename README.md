# faims3-qrcode-input

> QRCode input widget plugin for FAIMS3

[![NPM](https://img.shields.io/npm/v/@faims-project/faims3-qrcode-input.svg)](https://www.npmjs.com/package/@faims-project/faims3-qrcode-input) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save @faims-project/faims3-map-input
```

## Usage

```tsx
import React, { Component } from 'react'
import { Field, Form, Formik } from 'formik';
import QRCodeFormField from '@faims-project/faims3-qrcode-input'

class Example extends Component {
  render() {
      return <Formik>
                <Form>
                  <Field name="circle" featureType="Circle" component={QRCodeFormField} />
                </Form>
             </Formik>
  }
}
```

## License

[Apache2](http://www.apache.org/licenses/LICENSE-2.0) © [stevecassidy](https://github.com/stevecassidy)
