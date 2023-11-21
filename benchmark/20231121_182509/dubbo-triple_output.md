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
# Warmup Iteration   1: 4.738 ops/ms
# Warmup Iteration   2: 11.981 ops/ms
# Warmup Iteration   3: 12.193 ops/ms
Iteration   1: 12.511 ops/ms
Iteration   2: 12.549 ops/ms
Iteration   3: 12.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.552 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (12.511, 12.552, 12.595), stdev = 0.042
  CI (99.9%): [11.783, 13.321] (assumes normal distribution)


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
# Warmup Iteration   1: 8.487 ops/ms
# Warmup Iteration   2: 13.050 ops/ms
# Warmup Iteration   3: 12.949 ops/ms
Iteration   1: 12.890 ops/ms
Iteration   2: 12.915 ops/ms
Iteration   3: 12.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.912 ±(99.9%) 0.372 ops/ms [Average]
  (min, avg, max) = (12.890, 12.912, 12.930), stdev = 0.020
  CI (99.9%): [12.539, 13.284] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.772 ops/ms
# Warmup Iteration   2: 12.245 ops/ms
# Warmup Iteration   3: 12.604 ops/ms
Iteration   1: 12.620 ops/ms
Iteration   2: 12.525 ops/ms
Iteration   3: 12.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.590 ±(99.9%) 1.016 ops/ms [Average]
  (min, avg, max) = (12.525, 12.590, 12.624), stdev = 0.056
  CI (99.9%): [11.574, 13.605] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.683 ops/ms
# Warmup Iteration   2: 10.397 ops/ms
# Warmup Iteration   3: 10.405 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.499 ±(99.9%) 1.341 ops/ms [Average]
  (min, avg, max) = (10.430, 10.499, 10.576), stdev = 0.074
  CI (99.9%): [9.157, 11.840] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.295 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.003 ms/op
Iteration   1: 2.547 ±(99.9%) 0.005 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.575 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.547, 2.557, 2.575), stdev = 0.016
  CI (99.9%): [2.272, 2.842] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.721 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.004 ms/op
Iteration   1: 2.437 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.466 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (2.437, 2.466, 2.491), stdev = 0.027
  CI (99.9%): [1.965, 2.967] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.873 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.003 ms/op
Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
Iteration   3: 2.495 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.519 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (2.495, 2.519, 2.562), stdev = 0.038
  CI (99.9%): [1.833, 3.205] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
Iteration   3: 3.003 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.983, 3.001, 3.017), stdev = 0.017
  CI (99.9%): [2.687, 3.315] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.137 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  11.632 ms/op
                 createUser·p0.9999: 14.211 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  9.375 ms/op
                 createUser·p0.9999: 11.750 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.044 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 10.997 ms/op
                 createUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380376
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 182380 
    [ 2.500,  3.750) = 193096 
    [ 3.750,  5.000) = 3684 
    [ 5.000,  6.250) = 639 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.454 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  6.148 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  5.585 ms/op
                 existUser·p0.9999: 12.648 ms/op
                 existUser·p1.00:   12.861 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  8.570 ms/op
                 existUser·p0.9999: 11.779 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391268
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 195614 
    [ 2.500,  3.750) = 192601 
    [ 3.750,  5.000) = 2275 
    [ 5.000,  6.250) = 324 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =      6.527 ms/op
     p(99.9900) =     13.169 ms/op
     p(99.9990) =     13.567 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 3.832 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  7.274 ms/op
                 getUser·p0.9999: 16.040 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   2.505 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  6.767 ms/op
                 getUser·p0.9999: 12.224 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  7.156 ms/op
                 getUser·p0.9999: 11.471 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387212
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 193837 
    [ 2.500,  3.750) = 189006 
    [ 3.750,  5.000) = 3167 
    [ 5.000,  6.250) = 727 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      7.189 ms/op
     p(99.9900) =     13.809 ms/op
     p(99.9990) =     16.362 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.478 ms/op
                 listUser·p0.9999: 12.672 ms/op
                 listUser·p1.00:   15.237 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.920 ms/op
                 listUser·p0.9999: 10.125 ms/op
                 listUser·p1.00:   10.568 ms/op

Iteration   3: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.501 ms/op
                 listUser·p0.999:  9.990 ms/op
                 listUser·p0.9999: 11.147 ms/op
                 listUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317302
  mean =      3.023 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 87992 
    [ 2.500,  3.750) = 189582 
    [ 3.750,  5.000) = 32789 
    [ 5.000,  6.250) = 5559 
    [ 6.250,  7.500) = 610 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     12.079 ms/op
     p(99.9990) =     13.011 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.552 ± 0.769  ops/ms
ClientPb.existUser                       thrpt       3  12.912 ± 0.372  ops/ms
ClientPb.getUser                         thrpt       3  12.590 ± 1.016  ops/ms
ClientPb.listUser                        thrpt       3  10.499 ± 1.341  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.285   ms/op
ClientPb.existUser                        avgt       3   2.466 ± 0.501   ms/op
ClientPb.getUser                          avgt       3   2.519 ± 0.686   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.314   ms/op
ClientPb.createUser                     sample  380376   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.935           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.355           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.483           ms/op
ClientPb.existUser                      sample  391268   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.887           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.527           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.169           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.664           ms/op
ClientPb.getUser                        sample  387212   2.477 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.934           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.189           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.809           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.236           ms/op
ClientPb.listUser                       sample  317302   3.023 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.079           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.237           ms/op
