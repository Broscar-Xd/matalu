<template>
  <div>
    <div class="container-center">
      <div class="row">
        <div class="col-3">
          <div class="card" style="width: 18rem">
            <img
              src="https://live.staticflickr.com/65535/50574355157_5dd8d4158f.jpg"
              class="card-img-top"
              alt="https://live.staticflickr.com/65535/50574355157_5dd8d4158f.jpg"
            />
            <div class="card-body">
              <h5 class="card-title">Cuadrado</h5>
              <p class="card-text"></p>
              <form>
                    <label for="LCua" class="form-label">Lado</label>
                    <input type="text" class="form-control" id="LCua" value="000" required>
                    <div class="valid-feedback">
                    Looks good!
                    </div>
                    <br>

                <a href="#" class="btn btn-primary">Calcular</a>
                    <br><br>
                <label for="ACua" class="form-label">Respuesta</label>
                <input type="text" class="form-control" id="ACua" value="000">

              </form>
                <br>
            </div>
          </div>
        </div>

        <div class="col-3">
          <div class="card" style="width: 18rem">
            <img
              src="https://cosmodelcomo.com/wp-content/uploads/2020/05/rectangulo.jpg"
              class="card-img-top"
              alt="https://cosmodelcomo.com/wp-content/uploads/2020/05/rectangulo.jpg"
            />
            <div class="card-body">
              <h5 class="card-title">Rectángulo</h5>
              <p class="card-text"></p>
              <form>
                    <label for="LR" class="form-label">Lados</label>
                    <input type="text" class="form-control" id="LR1" value="000" required>
                    <input type="text" class="form-control" id="LR2" value="000" required>
                    <div class="valid-feedback">
                    Looks good!
                    </div>
                    <br>

                <a href="#" class="btn btn-primary">Calcular</a>
                    <br><br>
                <label for="ARec" class="form-label">Respuesta</label>
                <input type="text" class="form-control" id="ARec" value="000">

              </form>
                <br>
            </div>
          </div>
        </div>
        <div class="col-3">
          <div class="card" style="width: 18rem">
            <img
              src="data:image/jpeg;base64,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"
              class="card-img-top"
              alt="data:image/jpeg;base64,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"
            />
            <div class="card-body">
              <h5 class="card-title">Triángulo</h5>

              <form>
                    <label for="LTri" class="form-label">Lados</label>
                    <input type="text" class="form-control" id="LTri1" value="000" required>
                    <input type="text" class="form-control" id="LTri2" value="000" required>
                    <input type="text" class="form-control" id="LTri3" value="000" required>
                    <div class="valid-feedback">
                    Looks good!
                    </div>
                    <br>

                <a href="#" class="btn btn-primary">Calcular</a>
                    <br><br>
                <label for="AT" class="form-label">Respuesta</label>
                <input type="text" class="form-control" id="AT" value="000">

              </form>
                <br>
            </div>
          </div>
        </div>
        <div class="col-3">
          <div class="card" style="width: 18rem">
            <img
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8A3tX8ayJFgesE5wj8xVfXEqGoZDDb-F6FB5XfFSr_YcyKlm5VGisHnhtrgWMBHCu5qk&usqp=CAU"
              class="card-img-top"
              alt="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8A3tX8ayJFgesE5wj8xVfXEqGoZDDb-F6FB5XfFSr_YcyKlm5VGisHnhtrgWMBHCu5qk&usqp=CAU"
            />
            <div class="card-body">
              <h5 class="card-title">Circulo</h5>

              <form>
                    <label for="RCir" class="form-label">Radio</label>
                    <input type="text" class="form-control" id="RCir" value="000" required>
                    <div class="valid-feedback">
                    Looks good!
                    </div>
                    <br>

                <a href="#" class="btn btn-primary">Calcular</a>
                    <br><br>
                <label for="AC" class="form-label">Respuesta</label>
                <input type="text" class="form-control" id="AC" value="000">

              </form>
                <br>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Figuras",
};
</script>