# Xie stacking for LST players

Hi. I apologize in advance for being bad at explaining things.

If you know about Xie stacking, I'm 99.9% sure you are able to stack a center 4-wide combo. It looks something like this:

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/a2cfe940-7c8e-466b-b7fc-6db45defd23d)

But how do you open a 4-wide? Well, four.lol shows two examples: with a T piece and with a Z/S piece.

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/1601b26b-75bf-412a-a0ba-f174887c8087) ![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/3acf7e3c-7828-437e-86b8-aaa9842412df)

Have you ever thought about why these specific placements? Why not just start with a flat T next to the left wall and do JOL on the right wall?

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/d8bc3eec-7a18-46ce-9449-3170d21227ea)

How is this board state any different from the ones on four.lol? The answer is residue

## Residue

If you asked me about Xie stacking recently, I probably yapped to you about residue, but never properly explained what it is and how it is defined. When I talk about residue, what I truly mean is the extra blocks on top of a box shape. Any box shape works,
it doesn't matter what width and height it is. Here are a few examples, the grey part is the box and the colorful parts are the residue.

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/46b25419-540d-4ac2-9ebd-1fb4a3bd1f10)

This is an 8-wide stack with a 5 block residue.

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/b7db83ba-d9ee-4c1f-9af8-511f9ab089a6)


This is a 6-wide stack with a 2 block residue

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/722af9cc-25b0-4e52-9555-fbb21eb3d396)

This is a 9-wide stack with a 12 block residue

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/8580d254-7f25-48de-8e37-c7ce56708094)

And lastly, a 2w with 2 block residue and a 7w with a 13 block residue

## What makes 4-wide combo possible to combo...

...is the 3-block residue that your 4-wide well has. It is at the very bottom of the matrix, but nonetheless, it's still a 4-wide stack with a 3-residue in it.
![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/a3dfb9f2-d354-4ac4-820f-69f684a52963)

Now that you know that, you can make up your own 4-wide openers. You don't need a flat Z or T specifically, you just need to make sure that your opener adds those 3 blocks of residue to the 4-wide. You do this by having any 3 blocks of a piece inside the 4-wide, and one block on one of the sides:

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/52b440d0-38aa-45ad-8d4f-db28c4f6bcef)

## Real vs logical stacks

Sometimes, we don't have a real separation between stacks, but it's easier to think for us that they're separated. For example, an ST stack can have this kind of board state:

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/36829737-1a9c-4a4e-a3d2-3b66bc816e78)

If you understand everything so far, you'll see it as a 7-wide stack with 2 block residue. But in the mind of an ST stacker, it's still a 4-wide stack with 2 residue and a 3-wide stack with 0 residue (i.e. it's entirely flat). That's what I call a logical stack
separation - there's no wall, they're equal in height, and there is no well of any width between them - but we still separate them as if there's an invisible wall that must not be touched. Most ST stackers will always adhere to the following separation:

![image](https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/502781c4-4f06-4d80-ba5f-9a01989b440d)

Another example is in how most people describe the 6-wide stack of a 6-3 sprint. Separating it into "here goes O pieces, here goes S pieces, here goes Z pieces". We still have L, J, I, T pieces to place on the 6-wide, but people generally ignore them. You can watch
a sprint run where the separation is never broken in this sprint run by MAXICUBI. Very few people actually do this, by the way.

https://github.com/strawberrymilk1134/tetris-tutorials/assets/57014208/5a71969d-6dff-4fd0-9439-c559f8d8c03c

## So how does this all relate to Xie stacking?
