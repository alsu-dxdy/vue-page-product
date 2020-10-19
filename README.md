# vue-page-product

vue-page-product

https://alsu-dxdy.github.io/vue-page-product/

# Демо-страница товара, реализованная с помощью Vue.

Компонент product-review содержит форму обратной связи.
Компонент product-details содержит сведения о товаре.

## Реализованы такие вычисляемые свойства как:
- inStock() – выведение текстовых сообщений:
<p v-if="inStock">In Stock</p>
<p v-else>Out of Stock</p>
зависит от вычисления свойства inStock :  если в inStock попадет 0, то будет выведено сообщение: Out of Stock;

- middle() – средняя оценка товара, которую дали покупатели;

- countOfPositiveRecommend() - % покупателей, которые рекомендуют этот товар.

