<img src="https://kekse.biz/github.php?draw&override=github:levenshtein.js" />

# **`levenshtein.js`**
This is my implementation of the [levenshtein](https://www.google.com/search?q=levenshtein)
algorithm in plain JavaScript.

<br><br>

## Description
This algorithm calculates the 'distance' between words. It's often used to give a user
possible alternative words/commands/.. etc. if one typed in a 'wrong' command, e.g.

So when someone typed in a wrong command, he can see the probabilities
for other available words/commands/.. for this, the result will be sorted
by the distances (ascending).

<br>

## Implementation
Currently it only supports the matrix form (2D), even if there's also an alternative version
with only a vector/array (1D). So, this is prepared there, but not yet implemented. I heard
the vector form was a bit more efficient, but I don't know enough about all of this.

The regular (2D) form seems to properly work. Feel free to use it if you need it.

I decided to make my version public here because it was a bit hard till I finally understood
how it really works. And to be honest, even today I'm not totally sure.. but it works. **\^_\^**

<br>

## Usage
You should know how it works when you see it.

It's really not a big thing. I just give you the tip that there's one function to calculate
the distance between two words, and one main function to be called with many words to check.

<br>

## Download
* \[**2025-05-18**\] [`levenshtein.js`](src/levenshtein.js) (v**2.0.0**, c.a..);

<br>

## Configuration
Not that much.. only three `const` on top of the file for the default settings, which
can be changed on any call by the arguments (in any order).

* `DEFAULT_CASE_SENSITIVE`
* `DEFAULT_WITH_DISTANCES`
* `DEFAULT_DISTANCE`

The last one is there if you added the ['vector form'](#implementation), e.g.
So not really important for most of you.

## Extensions
I never really needed it, but as far as I know it's possible to extend it by weights or
so, based on the distance of the symbols on a keyboard. I just wanted you to know this,
but it's not implemented here.

<br><br>

# Contact
<img src="https://kekse.biz/github.php?override=github:levenshtein.js&draw&text=levenshtein.js@kekse.biz&angle=6&size=38pt&fg=150,20,90&font=OpenSans&ro&readonly&h=64&v=16" />

# Copyright and License
The Copyright is [(c) Sebastian Kucharczyk](COPYRIGHT.txt),
and it's licensed under the [MIT](LICENSE.txt) (also known as 'X' or 'X11' license).

<a href="https://kekse.biz/">
<img src="favicon.png" alt="Favicon" />
</a>

