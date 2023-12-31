Configuration
==========================

--------------------------------------------------------------------------

**GUI execution screen when button is clicked**

.. thumbnail:: /_images/start_gui/configuration.png

--------------------------------------------------------------------------

.. raw:: html

    <div style="background: #D3D3D3" class="admonition note custom">
        <p style="background: #A9A9A9" class="admonition-title">
            Traj Loop Mode
        </p>
        <ul>
            <li>
                Repeated trajectory driving
                <ul>
                    <li>If checked after executing Navigate Trajectories, trajectory driving will be performed repeatedly.</li>
                    <li>If you want to stop repetitive driving, you can uncheck and rerun Navigate Trajectories.</li>
                </ul>
            </li>
        </ul>
    </div>

--------------------------------------------------------------------------

.. raw:: html

    <div style="background: #D3D3D3" class="admonition note custom">
        <p style="background: #A9A9A9" class="admonition-title">
            Auto Charging
        </p>
        <ul>
            <li>
                Automatic charging in low battery condition
                <ul>
                    <li>The battery may discharge while driving if charging is not possible due to special circumstances (obstacles in front of the charging station, power failure)</li>
                    <li>In the case of scheduling, since the distance between charging times is long, when the low battery state is reached, the driving can be stopped and the charging process can be performed.</li>
                </ul>
            </li>
        </ul>
    </div>

--------------------------------------------------------------------------

.. raw:: html

    <div style="background: #D3D3D3" class="admonition note custom">
        <p style="background: #A9A9A9" class="admonition-title">
            Use Sonar
        </p>
        <ul>
            <li>
                Ultrasonic sensors used in front, back, left and right directions
                <ul>
                    <li>During autonomous driving, there are occasional cases where the driver leaves the map to evade.</li>
                    <li>In the driving algorithm, it reverses and moves away so that it can return to the normal driving state after a certain period of time.</li>
                    <li>If an obstacle is detected behind you while in reverse, the vehicle will stop.</li>
                </ul>
            </li>
        </ul>
    </div>