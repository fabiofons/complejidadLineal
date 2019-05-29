# Cambiando la Complejidad

    numDuplicados(str)
      obj = {} 
      for each char in str
        if obj.hasOwnProperty(char) 
          obj[char] += 1
        else
          obj[char] = 1
    
      llaves = Object.keys(obj)
      count = 0
      for each llave in llaves
        if obj[llave] > 1
          count++
    
    return count

Algoritmo de complejidad lineal **O(n+m)**

