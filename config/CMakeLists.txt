zephyr_library()

# behaviors.dtsi を読み込む場合の例
zephyr_library_sources_ifdef(CONFIG_ZMK_BEHAVIORS behaviors.dtsi)

