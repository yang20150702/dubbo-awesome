# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.332 ops/ms
# Warmup Iteration   2: 12.422 ops/ms
# Warmup Iteration   3: 12.525 ops/ms
Iteration   1: 12.760 ops/ms
Iteration   2: 12.652 ops/ms
Iteration   3: 12.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.780 ±(99.9%) 2.552 ops/ms [Average]
  (min, avg, max) = (12.652, 12.780, 12.930), stdev = 0.140
  CI (99.9%): [10.228, 15.333] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.414 ops/ms
# Warmup Iteration   2: 13.094 ops/ms
# Warmup Iteration   3: 13.328 ops/ms
Iteration   1: 13.063 ops/ms
Iteration   2: 13.198 ops/ms
Iteration   3: 13.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.139 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (13.063, 13.139, 13.198), stdev = 0.069
  CI (99.9%): [11.876, 14.402] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.563 ops/ms
# Warmup Iteration   2: 12.735 ops/ms
# Warmup Iteration   3: 12.845 ops/ms
Iteration   1: 13.064 ops/ms
Iteration   2: 13.101 ops/ms
Iteration   3: 13.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.070 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (13.045, 13.070, 13.101), stdev = 0.028
  CI (99.9%): [12.559, 13.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.576 ops/ms
# Warmup Iteration   2: 10.555 ops/ms
# Warmup Iteration   3: 10.629 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.674 ±(99.9%) 0.251 ops/ms [Average]
  (min, avg, max) = (10.659, 10.674, 10.686), stdev = 0.014
  CI (99.9%): [10.422, 10.925] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.825 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.003 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.479 ±(99.9%) 0.052 ms/op [Average]
  (min, avg, max) = (2.475, 2.479, 2.481), stdev = 0.003
  CI (99.9%): [2.427, 2.531] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.565 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.401 ±(99.9%) 0.005 ms/op
Iteration   2: 2.407 ±(99.9%) 0.005 ms/op
Iteration   3: 2.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.411 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.401, 2.411, 2.425), stdev = 0.012
  CI (99.9%): [2.185, 2.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.902 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
Iteration   2: 2.469 ±(99.9%) 0.003 ms/op
Iteration   3: 2.484 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.455, 2.469, 2.484), stdev = 0.015
  CI (99.9%): [2.203, 2.736] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.005 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
Iteration   3: 2.998 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.995 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.986, 2.995, 3.002), stdev = 0.008
  CI (99.9%): [2.850, 3.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  11.055 ms/op
                 createUser·p0.9999: 13.685 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  8.696 ms/op
                 createUser·p0.9999: 12.503 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  7.613 ms/op
                 createUser·p0.9999: 10.535 ms/op
                 createUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385654
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 188989 
    [ 2.500,  3.750) = 192350 
    [ 3.750,  5.000) = 3488 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     13.798 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.600 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.383 ±(99.9%) 0.005 ms/op
Iteration   1: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.392 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.545 ms/op
                 existUser·p0.999:  5.312 ms/op
                 existUser·p0.9999: 13.729 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   2: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  6.075 ms/op
                 existUser·p0.9999: 11.573 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   3: 2.411 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  7.585 ms/op
                 existUser·p0.9999: 11.842 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399200
  mean =      2.402 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 210126 
    [ 2.500,  3.750) = 185434 
    [ 3.750,  5.000) = 2762 
    [ 5.000,  6.250) = 347 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.425 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     12.583 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.006 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  6.687 ms/op
                 getUser·p0.9999: 15.434 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  9.471 ms/op
                 getUser·p0.9999: 14.318 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  6.724 ms/op
                 getUser·p0.9999: 10.557 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387217
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 194083 
    [ 2.500,  3.750) = 187735 
    [ 3.750,  5.000) = 4337 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      6.731 ms/op
     p(99.9900) =     14.149 ms/op
     p(99.9990) =     15.913 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.581 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
Iteration   1: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  8.667 ms/op
                 listUser·p0.9999: 11.760 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.556 ms/op
                 listUser·p0.9999: 11.736 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.634 ms/op
                 listUser·p0.9999: 10.833 ms/op
                 listUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321100
  mean =      2.987 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 97136 
    [ 2.500,  3.750) = 186166 
    [ 3.750,  5.000) = 30287 
    [ 5.000,  6.250) = 5856 
    [ 6.250,  7.500) = 847 
    [ 7.500,  8.750) = 307 
    [ 8.750, 10.000) = 184 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     11.682 ms/op
     p(99.9990) =     12.650 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.780 ± 2.552  ops/ms
ClientPb.existUser                       thrpt       3  13.139 ± 1.263  ops/ms
ClientPb.getUser                         thrpt       3  13.070 ± 0.511  ops/ms
ClientPb.listUser                        thrpt       3  10.674 ± 0.251  ops/ms
ClientPb.createUser                       avgt       3   2.479 ± 0.052   ms/op
ClientPb.existUser                        avgt       3   2.411 ± 0.226   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.266   ms/op
ClientPb.listUser                         avgt       3   2.995 ± 0.145   ms/op
ClientPb.createUser                     sample  385654   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.807           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.454           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.714           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  399200   2.402 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.657           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.425           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.512           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.583           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.778           ms/op
ClientPb.getUser                        sample  387217   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.708           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.731           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.149           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.040           ms/op
ClientPb.listUser                       sample  321100   2.987 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.880           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.929           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
