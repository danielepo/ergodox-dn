FROM dnlpozzobon/qmk

COPY . /qmk_firmware/keyboards/ergodox_ez/keymaps/daniele
COPY ./.docker/entrypoint.sh ./entrypoint.sh
RUN chmod +x ./entrypoint.sh

#ENTRYPOINT [ "make", "ergodox_ez:daniele" ]
# ENTRYPOINT [ "bash", "" ]

ENTRYPOINT [ "./entrypoint.sh" ]

# /qmk_firmware/teensyloader/Windows
# /qmk_firmware/.build#