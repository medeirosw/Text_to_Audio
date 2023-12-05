# Text_to_Audio
#   by Will Medeiros
# 
#  Web-based processesor that turns any text input into
#  a musical composition
#  System is based on a tokenized input where delineations are between
#  notes to be triggered and rests. The first character of each token
#  determines the note to be triggered, the last character determines
#  the duration of the note, and every other character in the token has the
#  potential to alter the note by adding effects. There are also certain
#  characters that change the compositional values, such as tempo, rest
#  length, and other modes.
#
