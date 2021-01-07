
# table funds
<div direction="ltr" style="display:flex;justify-content:start">
<table style="direction: rtl;background-color: red" >
    <tr><th>name</th><th>type</th><th>default</th><th>index</th></tr>
    <tr><th>id</th><th>int</th><th>none</th><th>primary</th></tr>
    <tr><th>name</th><th>varchar(200)</th><th>none</th><th>....</th></tr>
    <tr><th>user_id</th><th>int</th><th>none</th><th>index</th></tr>
    <tr><th>stock_count</th><th>int</th><th>none</th><th>....</th></tr>
    <tr><th>status</th><th>int</th><th>none</th><th>....</th></tr>
    <tr><th>currency</th><th>int</th><th>none</th><th>....</th></tr>
    <tr><th>stock_amount</th><th>int</th><th>none</th><th>....</th></tr>
    <tr><th>done_stock</th><th>int</th><th>0</th><th>....</th></tr>
    <tr><th>description</th><th>text</th><th>null</th><th>....</th></tr>
    <tr><th>created_at</th><th>timestamp</th><th>CURRENT_TIMESTAMP</th><th>....</th></tr>
    <tr><th>updated_at</th><th>timestamp</th><th>CURRENT_TIMESTAMP</th><th>....</th></tr> 
       
</table>
<div style="display: flex;justify-content: center">

#### Relation of fund table with : table status

<table>
    <tr><th>name</th><th>type</th><th>default</th><th>index</th></tr>
    <tr><th>id</th><th>int</th><th>none</th><th>primary</th></tr>
    <tr><th>name</th><th>varchar</th><th>none</th><th>....</th></tr>
</table>

#### Relation of fund table with : table currency

<table>
    <tr><th>name</th><th>type</th><th>default</th><th>index</th></tr>
    <tr><th>id</th><th>int</th><th>none</th><th>primary</th></tr>
    <tr><th>name</th><th>varchar</th><th>none</th><th>....</th></tr>
</table>
</div>


## Description of table fields funds

<table style="text-align: right">
    <tr><th>name</th><th>description</th></tr>
    <tr><th>id</th><td><b style="color:red">این فیلد شماره هر سطر رو درون خودش ذخیره می کند</b></td></tr>
    <tr><th>name</th><td><b> در این فیلد نام صندوق ذخیره می شود</b></td></tr>
    <tr><th>user_id</th><td><b>در این فیلد نام صاحب صندوق ذخیره می شود</b></td></tr>
    <tr><th>stock_count</th><td><b> تعداد سهم صندوق رو مشخص می کنه  </b></td></tr>
    <tr><th>status</th><td><b>این فیلد وظیفه دارد که وضعیت صندوق را که به سه حالت فعال ،غیرفعال ، ارشیو ، نیمه کاره را در خود ذخیره کند </b></td></tr>
    <tr><th>currency</th><td><b>در این فیلد واحد پول ذخیره می شود که معمولا به سه حالت ریال،تومان،دلار  می باشد </b></td></tr>
    <tr><th>stock_amount</th><td><b>در این فیلد ما مبلغ هر سهم رو  ذخیره می کنیم</b></td></tr>
    <tr><th>done_stock</th><td><b>در این فیلد تعدا سهم های انجام شده رو ذخیره می کنه مثلا اگر مدیر صندوق قرار باشه صندوق را متوقف کند تعداد سهم هایی که تا حالا برنده شدن در این فیلد ذخیره می شود </b></td></tr>
    <tr><th>description</th><td><b>در این فیلد ما توضیح کوتاهی در مورد صندوق ارائه می  کنیم و در داخل این فیلد ذخیره می کنیم </b></td></tr>
    <tr><th>created_at</th><td><b>در این فیلد تاریخ ایجاد صندوق  ذخیره می شود </b></td></tr>
    <tr><th>updated_at</th><td><b>در این فیلد تاریخ تغییر صندوق  ذخیره می شود </b></td></tr>
</table> 
</div>