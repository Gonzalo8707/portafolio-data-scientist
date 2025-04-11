
nombre_archivo = 'archivo.bin'
# Descargar el archivo desde Google Drive
gdown.download( 'https://drive.google.com/uc?id=191stTi4bltaYgZX5l-i2mcxjcxjuMNPK','archivo.bin', quiet=False)
# Cargar el archivo con KeyedVectors
word2vec_model_google = KeyedVectors.load_word2vec_format(nombre_archivo, binary=True)
