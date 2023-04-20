# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.687 ops/ms
# Warmup Iteration   2: 6.644 ops/ms
# Warmup Iteration   3: 9.531 ops/ms
Iteration   1: 9.274 ops/ms
Iteration   2: 10.214 ops/ms
Iteration   3: 10.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.887 ±(99.9%) 9.686 ops/ms [Average]
  (min, avg, max) = (9.274, 9.887, 10.214), stdev = 0.531
  CI (99.9%): [0.201, 19.573] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.728 ops/ms
# Warmup Iteration   2: 9.662 ops/ms
# Warmup Iteration   3: 9.880 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 9.981 ops/ms
Iteration   3: 10.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.135 ±(99.9%) 2.536 ops/ms [Average]
  (min, avg, max) = (9.981, 10.135, 10.251), stdev = 0.139
  CI (99.9%): [7.599, 12.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ops/ms
# Warmup Iteration   2: 8.715 ops/ms
# Warmup Iteration   3: 9.920 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.788 ops/ms
Iteration   3: 10.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.897 ±(99.9%) 5.203 ops/ms [Average]
  (min, avg, max) = (9.683, 9.897, 10.221), stdev = 0.285
  CI (99.9%): [4.695, 15.100] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.008 ops/ms
# Warmup Iteration   2: 7.248 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 8.628 ops/ms
Iteration   2: 8.391 ops/ms
Iteration   3: 8.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.542 ±(99.9%) 2.394 ops/ms [Average]
  (min, avg, max) = (8.391, 8.542, 8.628), stdev = 0.131
  CI (99.9%): [6.147, 10.936] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.464 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.002 ms/op
Iteration   1: 3.203 ±(99.9%) 0.008 ms/op
Iteration   2: 3.299 ±(99.9%) 0.005 ms/op
Iteration   3: 3.381 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.294 ±(99.9%) 1.627 ms/op [Average]
  (min, avg, max) = (3.203, 3.294, 3.381), stdev = 0.089
  CI (99.9%): [1.667, 4.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.791 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.002 ms/op
Iteration   1: 3.001 ±(99.9%) 0.008 ms/op
Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
Iteration   3: 3.202 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.081 ±(99.9%) 1.947 ms/op [Average]
  (min, avg, max) = (3.001, 3.081, 3.202), stdev = 0.107
  CI (99.9%): [1.134, 5.028] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.623 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.006 ms/op
Iteration   1: 3.429 ±(99.9%) 0.003 ms/op
Iteration   2: 3.126 ±(99.9%) 0.004 ms/op
Iteration   3: 3.123 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.226 ±(99.9%) 3.206 ms/op [Average]
  (min, avg, max) = (3.123, 3.226, 3.429), stdev = 0.176
  CI (99.9%): [0.020, 6.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.879 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.008 ms/op
Iteration   1: 3.709 ±(99.9%) 0.009 ms/op
Iteration   2: 3.750 ±(99.9%) 0.008 ms/op
Iteration   3: 3.808 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.755 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (3.709, 3.755, 3.808), stdev = 0.050
  CI (99.9%): [2.851, 4.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.653 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.009 ms/op
Iteration   1: 3.160 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  20.251 ms/op
                 createUser·p0.9999: 27.689 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  12.063 ms/op
                 createUser·p0.9999: 22.537 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.331 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  16.632 ms/op
                 createUser·p0.9999: 25.264 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297065
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23057 
    [ 2.500,  5.000) = 268377 
    [ 5.000,  7.500) = 4783 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     17.398 ms/op
     p(99.9900) =     26.584 ms/op
     p(99.9990) =     27.889 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.053 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  7.731 ms/op
                 existUser·p0.9999: 20.644 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.105 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  11.910 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309318
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10802 
    [ 2.500,  5.000) = 293912 
    [ 5.000,  7.500) = 3947 
    [ 7.500, 10.000) = 318 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     24.943 ms/op
     p(99.9990) =     26.723 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.654 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.009 ms/op
Iteration   1: 3.151 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  9.753 ms/op
                 getUser·p0.9999: 23.817 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  9.273 ms/op
                 getUser·p0.9999: 19.399 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 20.346 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304585
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7732 
    [ 2.500,  5.000) = 290403 
    [ 5.000,  7.500) = 5569 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     22.731 ms/op
     p(99.9990) =     24.706 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.340 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.012 ms/op
Iteration   1: 3.800 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  19.036 ms/op
                 listUser·p0.9999: 25.952 ms/op
                 listUser·p1.00:   26.739 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.321 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.096 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 14.311 ms/op
                 listUser·p1.00:   14.385 ms/op

Iteration   3: 3.697 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 17.477 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255829
  mean =      3.749 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 246767 
    [ 5.000,  7.500) = 6540 
    [ 7.500, 10.000) = 1616 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 353 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.321 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.444 ms/op
     p(99.9000) =     13.929 ms/op
     p(99.9900) =     24.453 ms/op
     p(99.9990) =     26.618 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.887 ± 9.686  ops/ms
ClientPb.existUser                       thrpt       3  10.135 ± 2.536  ops/ms
ClientPb.getUser                         thrpt       3   9.897 ± 5.203  ops/ms
ClientPb.listUser                        thrpt       3   8.542 ± 2.394  ops/ms
ClientPb.createUser                       avgt       3   3.294 ± 1.627   ms/op
ClientPb.existUser                        avgt       3   3.081 ± 1.947   ms/op
ClientPb.getUser                          avgt       3   3.226 ± 3.206   ms/op
ClientPb.listUser                         avgt       3   3.755 ± 0.905   ms/op
ClientPb.createUser                     sample  297065   3.229 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.253           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.398           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.584           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.574           ms/op
ClientPb.existUser                      sample  309318   3.101 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.943           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.099           ms/op
ClientPb.getUser                        sample  304585   3.149 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.552           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.731           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.871           ms/op
ClientPb.listUser                       sample  255829   3.749 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.321           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.444           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.453           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.739           ms/op
