# form-data-collector
collect and manage your html form data with myform by iysabox

the website link : https://iysabox.com/myform/

# steps :
1. create an account and login
2. copy your form special link ex: https://iysabox.com/myform/c/xxxxxxxxxx 
3. place the link in your action attribute 
<pre>&lt;form action="<span class="black">https://iysabox.com/myform/c/EfkpyZq44P</span>" method="post"&gt;
  &lt;input name="Email" id="email" type="email"&gt;
  &lt;type="hidden" value="MyForm1" name="form_name"&gt;
  &lt;type="hidden" name="is_bot"&gt; 
  &lt;button type="submit"&gt;Submit&lt;/button&gt;
&lt;/form&gt;</pre>

4. you are done!
# settings:
1.Form name <br>
By naming your forms, it will be easier to organize submittings. Add this line of code at the end of your form.
<pre class="code">&lt;input type="hidden" value="<span class="black">form Name Here</span>" name="form_name"&gt;</pre>

2.Honey pot<br>
 To filter bots add this input to the end of your form
<pre class="code">&lt;input type="hidden" name="is_bot"&gt;</pre>

3. Manage Empty submitting <br>
toggle it on or off to remove empty submitings

4.Unique users<br>
toggle it on or off to accept only unique users in the last 24 hour

5.Email<br>
toggle it On and add your email so you can get submited data in a message


