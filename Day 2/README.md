# Solutions

## Whats the new name for the cookie that was created from your account?

We are prompted to a website where we can register an account, but as soon as we register the account the site states we are not allowed to create an account.

No problem we still get a cookie from the action, checking the developer tools below the `Applications` tab we get the name **user-auth**

## What encoding type was used for the cookie value?

since a cookie can be encoded in any way or form we enter the value into the cyberchef decoder website tool thingy

when we decode the cookie cyberchef detected that the encoding is **hexadecimal**

## What object format is the data of the cookie stored in?

since decoding the cookie returns this string:

    {company: "The Best Festival Company", isregistered:"True", username:"admin"}
    
this type of attribute-value pairing is called **JSON**

## What is the value of the administrator cookie? (username = admin)

we take the JSON string and decode with hex using cyberchef

## What team environment is not responding?

modifying the cookie in the browser and refreshing the page prompts us to a page with information about the networks

we can see that the **HR** network isnt responding


## What team environment has a network warning?

**application**

