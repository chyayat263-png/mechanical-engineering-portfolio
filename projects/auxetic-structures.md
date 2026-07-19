# Bio-Inspired Auxetic Structures

## Project objective

Design, manufacture and experimentally compare lightweight bio-inspired auxetic structures for improved compression and impact-energy absorption.

## Why auxetic structures?

Auxetic structures have a negative Poisson’s ratio: their internal geometry enables an unusual lateral deformation response. The behaviour is controlled mainly by cell topology, rib orientation and deformation mechanisms rather than by base material alone. Potential applications include lightweight protective panels, crash absorbers, aerospace sandwich cores, helmets and biomedical structures.

## Designs investigated

1. **Spiderweb-inspired:** radial and concentric load paths intended to spread impact forces and delay crack growth.
2. **Trabecular-inspired:** irregular, interconnected paths inspired by trabecular bone.
3. **Hybrid:** combined geometric features intended to improve compression and densification behaviour.
4. **Honeycomb:** conventional cellular comparison.
5. **Bulk:** solid reference sample.

## Materials and fabrication

- Material: PLA+
- Process: fused deposition modelling / fused filament fabrication
- Printer: CreatBot F430
- Reported layer height: 0.1 mm
- Nozzle diameter: 0.4 mm
- Filament diameter: 1.75 mm
- Reported printing temperature: 210 °C

## Experimental methods

### Charpy impact testing

Impact specimens were compared using pendulum testing. The reported specimen profile was 114 × 15 × 5 mm with a V-notch, referencing ISO 179.

Absorbed energy was calculated from the pendulum motion:

```text
E = W × D × (cos β − cos α)
```

Specific impact energy:

```text
SEA = E / A
```

### Quasi-static compression

Compression specimens were reported as 40 × 40 × 25 mm, referencing ASTM D695. Load and displacement were converted into engineering stress and strain:

```text
Stress:              σ = F / A
Strain:              ε = ΔL / L₀
Young’s modulus:     E = σ / ε (initial linear region)
Energy absorption:  EA = ∫σ dε
```

## Results summary

### Impact

The spiderweb-inspired specimen achieved the best measured Charpy response:

- Absorbed energy: **0.287 J**
- Specific energy absorption: **174.0 kJ/m²**
- Improvement over bulk reference: **143%**
- Improvement over honeycomb: approximately **29%**

### Compression

- Hybrid maximum stress: **16.04 MPa**
- Spiderweb Young’s modulus: **63.30 MPa**
- Spiderweb plateau stress: **3.20 MPa**
- Hybrid produced the highest reported integrated compression energy-absorption value.

## Conclusions

Topology strongly affected mechanical performance. Spiderweb-inspired load paths were most effective in the tested impact comparison. The hybrid configuration was strongest for the reported compression energy-absorption response. The trabecular design provided a balanced, lower-force deformation response.

## Limitations

- Laboratory-scale polymer specimens
- One material system: PLA+
- Limited number of specimens
- Charpy impact testing is not ballistic certification
- Further high-velocity, repeated-impact and full-scale panel testing is required
- Detailed strain-field measurement would strengthen validation of local auxetic deformation

## Future development

- High-velocity impact and drop-weight testing
- Digital image correlation and high-speed imaging
- Geometry optimization and design-of-experiments studies
- Multi-material and functionally graded structures
- Layered protective panels combining spiderweb and hybrid topologies
- Aerospace sandwich-panel and crashworthiness applications
