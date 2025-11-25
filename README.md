
        function construirTr(paciente){
            var pacienteTr = document.createElement("tr");
            pacienteTr.classList.add("paciente");
            pacienteTr.appendChild(construirTd(paciente.nombre, "info-nombre"));
            pacienteTr.appendChild(construirTd(paciente.peso, "info-peso"));
            pacienteTr.appendChild(construirTd(paciente.altura, "info-altura"));
            pacienteTr.appendChild(construirTd(paciente.gordura, "info-gordura"));
            pacienteTr.appendChild(construirTd(paciente.imc,"info-imc"));
            return pacienteTr;
        };

            xhr.open("GET","https://raw.githubusercontent.com/AlexandraJossVA/Ajax-listado-dinamico/refs/heads/main/pacientes.json");

        
            });
            xhr.send();
        });
    </script>
</body>
</html>
