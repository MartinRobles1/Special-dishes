# Special-dishes
Es un programa que indica los ingredientes a utilizar en un determinado plato y el gasto total que se obtendrá por comprarlos. De esta forma el usuario final podra hacerle mas sencillo ordenas sus recetas de comidas.


print("special dishes")
verduras={"cebolla":5,"kion":45,"aji limo":485,"perejil":56,"lechuga":48,"pimiento":56}
tuberculos={"papa":91,"camote":74,"oca":35,"yuca":23,"mashua":46}
carnes={"res":50,"pescado":20,"pollo":15,"chancho":10,"conejo":30}
menestra={"lenteja":10,"frejol":13,"garbanzo":31,"alberja":22}
pescados={"bonito":12,"furel":16,","atun":32,"trucha":17}
otros={"sal":6,"mayonesa":1,"siyao":5,"huevo":6}

ingrediente=str(input("verduras:"))
for i in verduras.keys():
  if ingrediente in verduras:
    print{verduras[ingrediente]}
    ingrediente=str(input("verduras:"))
  elif ingrediente!=verduras.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      verduras.update({producto:costo})

ingrediente=str(input("tuberculos:"))
for i in tuberculos.keys():
  if ingrediente in tuberculos:
    print{tuberculos[ingrediente]}
    ingrediente=str(input("tuberculos:"))
  elif ingrediente!=tuberculos.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      tuberculos.update({producto:costo})

ingrediente=str(input("Menestra:"))
for i in menestra.keys():
  if ingrediente in menestra:
    print{menestra[ingrediente]}
    ingrediente=str(input("menestra:"))
  elif ingrediente!=menestra.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      menestra.update({producto:costo})

ingrediente=str(input("Pescado:"))
for i in pescado.keys():
  if ingrediente in pescado:
    print{pescado[ingrediente]}
    ingrediente=str(input("pescado:"))
  elif ingrediente!=pescado.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      pescado.update({producto:costo})

ingrediente=str(input("carnes:"))
for i in carnes.keys():
  if ingrediente in carnes:
    print{carnes[ingrediente]}
    ingrediente=str(input("carnes:"))
  elif ingrediente!=carnes.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      carnes.update({producto:costo})
      
ingrediente=str(input("otros:"))
for i in otros.keys():
  if ingrediente in otros:
    print{otros[ingrediente]}
    ingrediente=str(input("otros:"))
  elif ingrediente!=otros.has_key(i):
    if ingrediente=="nada mas":
        break
    if ingrediente!="nada mas":
      print("¿que producto es y cuanto cuesta?")
      producto=str(input("ingresar nuevo producto:"))
      costo=float(input("ingresar costo del producto:"))
      otros.update({producto:costo})
