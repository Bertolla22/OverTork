<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>OverTork – Lavagem Premium</title>

  <!-- Manifesto PWA -->
  <link rel="manifest" href="manifest.json" />
  <meta name="theme-color" content="#222" />

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #121212;
      color: #eee;
      margin: 0; padding: 20px;
      display: flex; flex-direction: column; align-items: center;
      justify-content: center; min-height: 100vh;
    }
    #installBanner {
      background: #ff5722;
      padding: 15px 20px;
      border-radius: 8px;
      position: fixed;
      bottom: 20px;
      left: 20px;
      right: 20px;
      display: none;
      align-items: center;
      justify-content: space-between;
      font-weight: bold;
      cursor: pointer;
      z-index: 1000;
    }
    #installBanner button {
      background: #fff;
      border: none;
      padding: 8px 15px;
      border-radius: 6px;
      font-weight: normal;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <h1>OverTork – Lavagem Premium</h1>
  <p>Seu carro premium cuidado em casa.</p>

  <div id="installBanner">
    Adicione o OverTork à sua tela inicial para uma experiência completa!
    <button id="btnInstall">Adicionar</button>
    <button id="btnDismiss">X</button>
  </div>

  <script>
    let deferredPrompt;
    const installBanner = document.getElementById('installBanner');
    const btnInstall = document.getElementById('btnInstall');
    const btnDismiss = document.getElementById('btnDismiss');

    window.addEventListener('beforeinstallprompt', (e) => {
      e.preventDefault();
      deferredPrompt = e;
      installBanner.style.display = 'flex';
    });

    btnInstall.addEventListener('click', async () => {
      installBanner.style.display = 'none';
      if (deferredPrompt) {
        deferredPrompt.prompt();
        deferredPrompt = null;
      }
    });

    btnDismiss.addEventListener('click', () => {
      installBanner.style.display = 'none';
    });
  </script>

  <script>
    if ('serviceWorker' in navigator) {
      navigator.serviceWorker.register('sw.js')
        .then(() => console.log('Service Worker registrado.'))
        .catch(err => console.error('Erro no SW:', err));
    }
  </script>

</body>
</html>
