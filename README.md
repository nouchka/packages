# packages

# To create GPG key

+	docker run -it --rm ubuntu /bin/bash
+	apt-get install gpg
+	gpg --full-generate-key
+	gpg --export-secret-keys --armor KEY_ID | base64 -w 0
