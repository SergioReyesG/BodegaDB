CREATE TABLE PRODUCTOS(
  idprod char(7) PRIMARY KEY,
  descripcion varchar2(25),
  existencia  int
);

CREATE TABLE PEDIDOS(
  idpedido char(7),
  idprod char(7),
  cantidad int,
  CONSTRAINT FK1 FOREIGN KEY (idprod) REFERENCES PRODUCTOS (idprod)
);
