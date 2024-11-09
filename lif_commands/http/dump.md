# HTTP Brain Dump

mux.HandleFunc("/", func(w http.ResponseWriter, r *http.Request) {
    http.Redirect(w, r, "/app/", http.StatusMovedPermanently)
})