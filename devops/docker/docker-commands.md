# docker commands

{% embed url="https://linoxide.com/linux-how-to/docker-commands-cheat-sheet/" %}

{% embed url="https://github.com/wsargent/docker-cheat-sheet" %}

## Management Commands

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">builder</td>
      <td style="text-align:left">Manage builds</td>
      <td style="text-align:left">
        <ul>
          <li>prune - remove build cache</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">image</td>
      <td style="text-align:left">Manage images</td>
      <td style="text-align:left">
        <ul>
          <li><b>build</b> - Build an image from a Dockerfile</li>
          <li><b>history</b> - Show the history of an image</li>
          <li>import - Import the contents from a tarball to create a filesystem image</li>
          <li>inspect - Display detailed information on one or more images</li>
          <li>load - Load an image from a tar archive or STDIN</li>
          <li>ls - List images</li>
          <li>prune - Remove unused images</li>
          <li>pull - Pull an image or a repository from a registry</li>
          <li>push - Push an image or a repository to a registry</li>
          <li>rm - Remove one or more images</li>
          <li>save - Save one or more images to a tar archive (streamed to STDOUT by
            default)</li>
          <li>tag - Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">container</td>
      <td style="text-align:left">Manage containers</td>
      <td style="text-align:left">
        <p><b>Lifecycle</b>
        </p>
        <p>&lt;b&gt;&lt;/b&gt;</p>
        <ul>
          <li>attach - Attach local standard input, output, and error streams to a running
            container</li>
          <li>commit - Create a new image from a container&apos;s changes</li>
          <li>cp - Copy files/folders between a container and the local filesystem</li>
          <li>create - Create a new container</li>
          <li>diff Inspect changes to files or directories on a container&apos;s filesystem</li>
          <li>exec - Run a command in a running container</li>
          <li>export - Export a container&apos;s filesystem as a tar archive</li>
          <li>inspect - Display detailed information on one or more containers</li>
          <li>kill - Kill one or more running containers</li>
          <li>logs - Fetch the logs of a container</li>
          <li>ls - List containers</li>
          <li>pause - Pause all processes within one or more containers</li>
          <li>port - List port mappings or a specific mapping for the container</li>
          <li>prune - Remove all stopped containers</li>
          <li>rename - Rename a container</li>
          <li>restart - Restart one or more containers</li>
          <li>rm - Remove one or more containers</li>
          <li>run - Run a command in a new container</li>
          <li>start - Start one or more stopped containers</li>
          <li>stats - Display a live stream of container(s) resource usage statistics</li>
          <li>stop - Stop one or more running containers</li>
          <li>top - Display the running processes of a container</li>
          <li>unpause - Unpause all processes within one or more containers</li>
          <li>update - Update configuration of one or more containers</li>
          <li>wait - Block until one or more containers stop, then print their exit
            codes</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">volume</td>
      <td style="text-align:left">Manage volumes</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">network</td>
      <td style="text-align:left">Manage networks</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">plugin</td>
      <td style="text-align:left">Manage plugins</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">secret</td>
      <td style="text-align:left">Manage Docker secrets</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">service</td>
      <td style="text-align:left">Manage services</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">stack</td>
      <td style="text-align:left">Manage Docker stacks</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">system</td>
      <td style="text-align:left">Manage Docker</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">trust</td>
      <td style="text-align:left">Manage trust on Docker images</td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>## Swarm Management Command

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">config</td>
      <td style="text-align:left">Manage Docker configs</td>
      <td style="text-align:left">
        <ul>
          <li>create</li>
          <li>inspect</li>
          <li>ls</li>
          <li>rm</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">node</td>
      <td style="text-align:left">Manage Swarm nodes</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">swarm</td>
      <td style="text-align:left">Manage Swarm</td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>## Subcommands

**docker image**

\*\*\*\*

**docker container**

\*\*\*\*

**docker volume**

\*\*\*\*

