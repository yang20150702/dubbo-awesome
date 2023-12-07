# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.555 ops/ms
# Warmup Iteration   2: 11.822 ops/ms
# Warmup Iteration   3: 12.278 ops/ms
Iteration   1: 12.527 ops/ms
Iteration   2: 12.689 ops/ms
Iteration   3: 12.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.635 ±(99.9%) 1.707 ops/ms [Average]
  (min, avg, max) = (12.527, 12.635, 12.689), stdev = 0.094
  CI (99.9%): [10.927, 14.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.889 ops/ms
# Warmup Iteration   2: 13.175 ops/ms
# Warmup Iteration   3: 13.022 ops/ms
Iteration   1: 13.070 ops/ms
Iteration   2: 13.298 ops/ms
Iteration   3: 13.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.209 ±(99.9%) 2.227 ops/ms [Average]
  (min, avg, max) = (13.070, 13.209, 13.298), stdev = 0.122
  CI (99.9%): [10.982, 15.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.680 ops/ms
# Warmup Iteration   2: 12.801 ops/ms
# Warmup Iteration   3: 12.991 ops/ms
Iteration   1: 13.090 ops/ms
Iteration   2: 12.930 ops/ms
Iteration   3: 12.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.988 ±(99.9%) 1.616 ops/ms [Average]
  (min, avg, max) = (12.930, 12.988, 13.090), stdev = 0.089
  CI (99.9%): [11.372, 14.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.818 ops/ms
# Warmup Iteration   2: 10.533 ops/ms
# Warmup Iteration   3: 10.728 ops/ms
Iteration   1: 10.846 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.793 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (10.735, 10.793, 10.846), stdev = 0.056
  CI (99.9%): [9.779, 11.807] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
Iteration   3: 2.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (2.509, 2.534, 2.567), stdev = 0.030
  CI (99.9%): [1.987, 3.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.746 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.395 ±(99.9%) 0.003 ms/op
Iteration   1: 2.410 ±(99.9%) 0.003 ms/op
Iteration   2: 2.396 ±(99.9%) 0.003 ms/op
Iteration   3: 2.395 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.400 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (2.395, 2.400, 2.410), stdev = 0.008
  CI (99.9%): [2.248, 2.553] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.752 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.003 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (2.450, 2.468, 2.483), stdev = 0.017
  CI (99.9%): [2.166, 2.769] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.632 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.005 ms/op
Iteration   1: 2.956 ±(99.9%) 0.004 ms/op
Iteration   2: 2.939 ±(99.9%) 0.005 ms/op
Iteration   3: 2.935 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.943 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (2.935, 2.943, 2.956), stdev = 0.011
  CI (99.9%): [2.741, 3.146] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.550 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  11.823 ms/op
                 createUser·p0.9999: 14.402 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  9.384 ms/op
                 createUser·p0.9999: 12.075 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 2.550 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 52.752 ms/op
                 createUser·p1.00:   53.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377921
  mean =      2.537 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 377029 
    [ 5.000, 10.000) = 572 
    [10.000, 15.000) = 286 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     14.470 ms/op
     p(99.9990) =     53.361 ms/op
     p(99.9999) =     53.543 ms/op
    p(100.0000) =     53.543 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.599 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.561 ms/op
                 existUser·p0.999:  6.030 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.284 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   15.729 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  8.063 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395755
  mean =      2.423 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 200637 
    [ 2.500,  3.750) = 191999 
    [ 3.750,  5.000) = 2427 
    [ 5.000,  6.250) = 250 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      5.800 ms/op
     p(99.9900) =     13.565 ms/op
     p(99.9990) =     15.584 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.006 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  5.860 ms/op
                 getUser·p0.9999: 13.318 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  6.727 ms/op
                 getUser·p0.9999: 14.516 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.018 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 16.107 ms/op
                 getUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390871
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 198675 
    [ 2.500,  3.750) = 187809 
    [ 3.750,  5.000) = 3415 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.756 ms/op
     p(99.9900) =     14.516 ms/op
     p(99.9990) =     16.408 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.760 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.009 ms/op
Iteration   1: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  9.766 ms/op
                 listUser·p0.9999: 11.682 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 11.926 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.555 ms/op
                 listUser·p0.9999: 11.485 ms/op
                 listUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319703
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 93772 
    [ 2.500,  3.750) = 187900 
    [ 3.750,  5.000) = 31352 
    [ 5.000,  6.250) = 5355 
    [ 6.250,  7.500) = 577 
    [ 7.500,  8.750) = 140 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     11.731 ms/op
     p(99.9990) =     12.232 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.635 ± 1.707  ops/ms
ClientPb.existUser                       thrpt       3  13.209 ± 2.227  ops/ms
ClientPb.getUser                         thrpt       3  12.988 ± 1.616  ops/ms
ClientPb.listUser                        thrpt       3  10.793 ± 1.014  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.547   ms/op
ClientPb.existUser                        avgt       3   2.400 ± 0.153   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.302   ms/op
ClientPb.listUser                         avgt       3   2.943 ± 0.203   ms/op
ClientPb.createUser                     sample  377921   2.537 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.836           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.388           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.470           ms/op
ClientPb.createUser:createUser·p1.00    sample          53.543           ms/op
ClientPb.existUser                      sample  395755   2.423 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.886           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.800           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.565           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.729           ms/op
ClientPb.getUser                        sample  390871   2.454 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.642           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.756           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.516           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.613           ms/op
ClientPb.listUser                       sample  319703   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.929           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.731           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.370           ms/op
