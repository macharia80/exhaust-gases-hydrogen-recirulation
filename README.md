# <mxGraphModel dx="1426" dy="777" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" background="#ffffff" math="0" shadow="0">
  <root>
    <mxCell id="0"/>
    <mxCell id="1" parent="0"/>
    <mxCell id="2" value="Engine<br>(Gasoline)" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="80" y="240" width="120" height="60" as="geometry"/>
    </mxCell>
    <mxCell id="3" value="" style="endArrow=classic;html=1;exitX=1;exitY=0.5;exitPerimeter=0;" edge="1" parent="1" source="2">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="220" y="270" as="sourcePoint"/>
        <mxPoint x="280" y="270" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="4" value="Particulate<br>Filter" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="280" y="240" width="80" height="60" as="geometry"/>
    </mxCell>
    <mxCell id="5" value="" style="endArrow=classic;html=1;entryX=0;entryY=0.5;exitX=1;exitY=0.5;" edge="1" parent="1" source="4" target="6">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="380" y="270" as="sourcePoint"/>
        <mxPoint x="430" y="270" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="6" value="Heat<br>Exchanger<br>(Cool to 350–400°C)" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="440" y="240" width="100" height="60" as="geometry"/>
    </mxCell>
    <mxCell id="7" value="" style="endArrow=classic;html=1;exitX=1;exitY=0.5;" edge="1" parent="1" source="6">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="560" y="270" as="sourcePoint"/>
        <mxPoint x="620" y="270" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="8" value="H₂-Selective<br>Membrane<br>Module" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="620" y="240" width="100" height="60" as="geometry"/>
    </mxCell>
    <mxCell id="9" value="" style="endArrow=classic;html=1;exitX=0.5;exitY=0;exitPerimeter=0;" edge="1" parent="1" source="8">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="660" y="230" as="sourcePoint"/>
        <mxPoint x="670" y="160" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="10" value="H₂ Accumulator<br>Tank<br>(with safety valve)" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="620" y="80" width="100" height="60" as="geometry"/>
    </mxCell>
    <mxCell id="11" value="" style="endArrow=classic;html=1;exitX=0.5;exitY=0;entryX=0.5;entryY=1;" edge="1" parent="1" source="10" target="12">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="670" y="70" as="sourcePoint"/>
        <mxPoint x="670" y="20" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="12" value="H₂ Injector" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="620" y="20" width="100" height="30" as="geometry"/>
    </mxCell>
    <mxCell id="13" value="" style="endArrow=classic;html=1;exitX=0;exitY=0.5;entryX=1;entryY=0.5;" edge="1" parent="1" source="12" target="14">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="610" y="40" as="sourcePoint"/>
        <mxPoint x="560" y="40" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="14" value="Intake<br>Manifold" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="440" y="20" width="100" height="60" as="geometry"/>
    </mxCell>
    <mxCell id="15" value="Exhaust Flow" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
      <mxGeometry x="210" y="250" width="70" height="20" as="geometry"/>
    </mxCell>
    <mxCell id="16" value="H₂ Flow" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
      <mxGeometry x="680" y="190" width="60" height="20" as="geometry"/>
    </mxCell>
    <mxCell id="17" value="Control Unit<br>(Arduino / ECU)<br>• H₂ Sensor<br>• O₂ Sensor<br>• Timing Adjust" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="780" y="120" width="120" height="80" as="geometry"/>
    </mxCell>
    <mxCell id="18" value="" style="endArrow=none;html=1;entryX=0;entryY=0.5;exitX=0;exitY=0.5;" edge="1" parent="1" source="17" target="10">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="770" y="160" as="sourcePoint"/>
        <mxPoint x="720" y="160" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="19" value="" style="endArrow=none;html=1;entryX=0;entryY=0.5;exitX=0.25;exitY=1;" edge="1" parent="1" source="17" target="12">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="810" y="210" as="sourcePoint"/>
        <mxPoint x="760" y="210" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="20" value="Flame<br>Arrester" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
      <mxGeometry x="620" y="140" width="100" height="20" as="geometry"/>
    </mxCell>
    <mxCell id="21" value="" style="endArrow=classic;html=1;entryX=0.5;entryY=1;exitX=0.5;exitY=0;" edge="1" parent="1" source="20" target="10">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="670" y="130" as="sourcePoint"/>
        <mxPoint x="670" y="80" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
    <mxCell id="22" value="" style="endArrow=classic;html=1;entryX=0.5;entryY=1;exitX=0.5;exitY=0;" edge="1" parent="1" source="8" target="20">
      <mxGeometry width="50" height="50" relative="1" as="geometry">
        <mxPoint x="670" y="230" as="sourcePoint"/>
        <mxPoint x="670" y="180" as="targetPoint"/>
      </mxGeometry>
    </mxCell>
  </root>
</mxGraphModel>exhaust-gases-hydrogen-recirulation