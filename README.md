# Norm-Vectors

def norm1(V):
  result = 0
  for i in range(len(V)):
    result = result + abs(V[i])
  return result

def norm2(V):
  result = 0
  for i in range(len(V)):
    result = result + abs(V[i])
  result = result**.5
  return result

def norm3(V):
  result = 0
  for i in range(len(V)):
    if result <= abs(V[i]):
      result = abs(V[i])
  return result
