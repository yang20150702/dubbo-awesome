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
# Warmup Iteration   1: 4.976 ops/ms
# Warmup Iteration   2: 12.209 ops/ms
# Warmup Iteration   3: 12.378 ops/ms
Iteration   1: 12.715 ops/ms
Iteration   2: 12.589 ops/ms
Iteration   3: 12.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.684 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (12.589, 12.684, 12.750), stdev = 0.084
  CI (99.9%): [11.145, 14.224] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.649 ops/ms
# Warmup Iteration   2: 13.168 ops/ms
# Warmup Iteration   3: 13.125 ops/ms
Iteration   1: 13.163 ops/ms
Iteration   2: 13.125 ops/ms
Iteration   3: 13.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.174 ±(99.9%) 1.011 ops/ms [Average]
  (min, avg, max) = (13.125, 13.174, 13.234), stdev = 0.055
  CI (99.9%): [12.163, 14.186] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.931 ops/ms
# Warmup Iteration   2: 12.617 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 12.794 ops/ms
Iteration   2: 12.898 ops/ms
Iteration   3: 12.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.797 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (12.698, 12.797, 12.898), stdev = 0.100
  CI (99.9%): [10.971, 14.622] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.717 ops/ms
# Warmup Iteration   2: 10.479 ops/ms
# Warmup Iteration   3: 10.428 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.511 ops/ms
Iteration   3: 10.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.529 ±(99.9%) 1.136 ops/ms [Average]
  (min, avg, max) = (10.478, 10.529, 10.599), stdev = 0.062
  CI (99.9%): [9.394, 11.665] (assumes normal distribution)


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.003 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (2.515, 2.524, 2.541), stdev = 0.014
  CI (99.9%): [2.264, 2.785] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.706 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.003 ms/op
Iteration   1: 2.427 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.424 ±(99.9%) 0.077 ms/op [Average]
  (min, avg, max) = (2.419, 2.424, 2.427), stdev = 0.004
  CI (99.9%): [2.347, 2.502] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.468, 2.473, 2.475), stdev = 0.004
  CI (99.9%): [2.401, 2.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.588 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
Iteration   3: 2.997 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.012 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.997, 3.012, 3.023), stdev = 0.014
  CI (99.9%): [2.764, 3.259] (assumes normal distribution)


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.678 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  9.643 ms/op
                 createUser·p0.9999: 13.686 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.518 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  10.089 ms/op
                 createUser·p0.9999: 12.283 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  7.915 ms/op
                 createUser·p0.9999: 13.949 ms/op
                 createUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383212
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 185092 
    [ 2.500,  3.750) = 193710 
    [ 3.750,  5.000) = 3376 
    [ 5.000,  6.250) = 528 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.073 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.784 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  6.283 ms/op
                 existUser·p0.9999: 13.300 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.915 ms/op
                 existUser·p0.9999: 13.402 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  6.005 ms/op
                 existUser·p0.9999: 11.106 ms/op
                 existUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394158
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 196867 
    [ 2.500,  3.750) = 194492 
    [ 3.750,  5.000) = 1984 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =      6.070 ms/op
     p(99.9900) =     13.182 ms/op
     p(99.9990) =     14.929 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  8.228 ms/op
                 getUser·p0.9999: 13.342 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.838 ms/op
                 getUser·p0.999:  9.648 ms/op
                 getUser·p0.9999: 12.209 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  8.106 ms/op
                 getUser·p0.9999: 10.734 ms/op
                 getUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382932
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 187858 
    [ 2.500,  3.750) = 188950 
    [ 3.750,  5.000) = 4615 
    [ 5.000,  6.250) = 968 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      8.865 ms/op
     p(99.9900) =     12.567 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.009 ms/op
Iteration   1: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.568 ms/op
                 listUser·p0.9999: 11.321 ms/op
                 listUser·p1.00:   12.321 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 11.710 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 11.174 ms/op
                 listUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318605
  mean =      3.010 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 90314 
    [ 2.500,  3.750) = 189221 
    [ 3.750,  5.000) = 32170 
    [ 5.000,  6.250) = 5617 
    [ 6.250,  7.500) = 431 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 182 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.452 ms/op
     p(99.9990) =     12.410 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


# Run complete. Total time: 00:12:56

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.684 ± 1.540  ops/ms
ClientPb.existUser                       thrpt       3  13.174 ± 1.011  ops/ms
ClientPb.getUser                         thrpt       3  12.797 ± 1.825  ops/ms
ClientPb.listUser                        thrpt       3  10.529 ± 1.136  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.261   ms/op
ClientPb.existUser                        avgt       3   2.424 ± 0.077   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.072   ms/op
ClientPb.listUser                         avgt       3   3.012 ± 0.247   ms/op
ClientPb.createUser                     sample  383212   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.518           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.073           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.664           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  394158   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.696           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.070           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.024           ms/op
ClientPb.getUser                        sample  382932   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.846           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.865           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.567           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.910           ms/op
ClientPb.listUser                       sample  318605   3.010 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.452           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.616           ms/op
