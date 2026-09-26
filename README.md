
        console.error(err);
        let msg = 'Uy, hubo un problemita técnico 😅. Intentá de nuevo en un momento.';
        if (err.message && err.message.includes('Failed to fetch')) {
          msg = '⚠️ No se pudo conectar con la IA.\n\nEsto pasa porque el archivo se
