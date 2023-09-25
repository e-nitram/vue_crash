## Select

Display a dropdown list of items.

<ex-code name="ex-select-basic"></ex-code>

<ex-code name="ex-select-size"></ex-code>

<ex-code name="ex-select-simple">

Style without icons.

</ex-code>

<ex-code name="ex-select-disabled">

You can disable one <code>Item</code> or all <code>Option</code>.

</ex-code>

<ex-footer edit-link="https://github.com/geist-org/vue/edit/master/docs/en-us/components/select.md">
<h3>zi-select</h3>

| Attribute        | Description            | Type                        | Accepted values             | Default |
| ---------------- | ---------------------- | --------------------------- | --------------------------- | ------- |
| **v-model**      | binding value[v-model] | `string | boolean | number` | -                           | -       |
| **size**         | select size            | `string`                    | `mini` / `small` / `medium` | -       |
| **autocomplete** | native attribute       | `boolean`                   | `true` / `false`            | `false` |
| **autofocus**    | native attribute       | `boolean`                   | `true` / `false`            | `false` |
| **form**         | native attribute       | `string`                    | -                           | -       |
| **name**         | native attribute       | `string`                    | -                           | -       |
| **disabled**     | disable select         | `boolean`                   | `true` / `false`            | `false` |
| **simple**       | simple mode            | `boolean`                   | `true` / `false`            | `false` |

<br/>
<h3>zi-option</h3>

| Attribute    | Description            | Type              | Accepted values  | Default |
| ------------ | ---------------------- | ----------------- | ---------------- | ------- |
| **v-model**  | binding value[v-model] | `string | number` | -                | -       |
| **label**    | text of label          | `string`          | -                | -       |
| **disabled** | disable an option      | `boolean`         | `true` / `false` | `false` |

</ex-footer>
