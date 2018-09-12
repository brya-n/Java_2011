# Java_2011
# In 2011 I was studying modules with the Open University in Java
# One of the courses required me as part of a module project to:
#
# “There should be two or more objects interacting with each other, and none should leave the confines of the box”
#
# The resulting single jar application that I created:
# Primary colour orbs (color in Java!) bounce around a bounded box
# You control a square with colour r=127, g=127, b=127 with the aim to collide with a sphere
# On colliding with a sphere:
#   Alpha channel of sphere --
#   // this is simulating being drained
#   If prime colour of sphere in the rgb colour channel of box < 255 && rgb channel
#      Prime colour channel of box ++
#   Else
#      For each non-prime colour channel that is  > 0 
#      --
#
#  Controls
#  Q: Quit (or the button)
#  1: Slow down square (r, g, b = 127, 127, 127 )
#  2: Speed up square
#  Navigate:
#  Cursor keys 
#
#  Futher information
#  Sound = none
#  Score = none
#
#  bray-n
