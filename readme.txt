{% assign current_variant = product.selected_or_first_available_variant %}
<div class="product-block" style="margin-top:20px;">
{%- render 'product-form',
form_id: form_id,
product: product,
show_dynamic_checkout: block.settings.show_dynamic_checkout,
current_variant: current_variant
-%}
</div>