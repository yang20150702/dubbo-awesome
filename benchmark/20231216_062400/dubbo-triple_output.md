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
# Warmup Iteration   1: 4.609 ops/ms
# Warmup Iteration   2: 12.141 ops/ms
# Warmup Iteration   3: 12.480 ops/ms
Iteration   1: 12.545 ops/ms
Iteration   2: 12.772 ops/ms
Iteration   3: 12.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.710 ±(99.9%) 2.633 ops/ms [Average]
  (min, avg, max) = (12.545, 12.710, 12.813), stdev = 0.144
  CI (99.9%): [10.077, 15.344] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.091 ops/ms
# Warmup Iteration   2: 13.254 ops/ms
# Warmup Iteration   3: 13.073 ops/ms
Iteration   1: 13.042 ops/ms
Iteration   2: 13.222 ops/ms
Iteration   3: 13.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.105 ±(99.9%) 1.846 ops/ms [Average]
  (min, avg, max) = (13.042, 13.105, 13.222), stdev = 0.101
  CI (99.9%): [11.259, 14.951] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.942 ops/ms
# Warmup Iteration   2: 12.751 ops/ms
# Warmup Iteration   3: 12.800 ops/ms
Iteration   1: 13.234 ops/ms
Iteration   2: 12.934 ops/ms
Iteration   3: 12.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.025 ±(99.9%) 3.306 ops/ms [Average]
  (min, avg, max) = (12.908, 13.025, 13.234), stdev = 0.181
  CI (99.9%): [9.719, 16.331] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.614 ops/ms
# Warmup Iteration   2: 10.479 ops/ms
# Warmup Iteration   3: 10.482 ops/ms
Iteration   1: 10.769 ops/ms
Iteration   2: 10.754 ops/ms
Iteration   3: 10.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.719 ±(99.9%) 1.353 ops/ms [Average]
  (min, avg, max) = (10.634, 10.719, 10.769), stdev = 0.074
  CI (99.9%): [9.366, 12.071] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.878 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.500 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.480, 2.500, 2.521), stdev = 0.021
  CI (99.9%): [2.123, 2.877] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.616 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.004 ms/op
Iteration   1: 2.436 ±(99.9%) 0.003 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.436, 2.455, 2.474), stdev = 0.019
  CI (99.9%): [2.106, 2.804] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.488 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (2.469, 2.488, 2.502), stdev = 0.017
  CI (99.9%): [2.179, 2.797] (assumes normal distribution)


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
Iteration   2: 2.944 ±(99.9%) 0.005 ms/op
Iteration   3: 2.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.959 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.944, 2.959, 2.981), stdev = 0.020
  CI (99.9%): [2.599, 3.318] (assumes normal distribution)


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.295 ms/op
                 createUser·p0.9999: 14.234 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.531 ms/op
                 createUser·p0.999:  8.684 ms/op
                 createUser·p0.9999: 11.551 ms/op
                 createUser·p1.00:   12.370 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  8.233 ms/op
                 createUser·p0.9999: 11.375 ms/op
                 createUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382991
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 186650 
    [ 2.500,  3.750) = 192695 
    [ 3.750,  5.000) = 2732 
    [ 5.000,  6.250) = 417 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     13.119 ms/op
     p(99.9990) =     14.550 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.391 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  5.992 ms/op
                 existUser·p0.9999: 13.910 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.283 ms/op
                 existUser·p0.9999: 11.174 ms/op
                 existUser·p1.00:   11.469 ms/op

Iteration   3: 2.400 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   2.987 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  6.093 ms/op
                 existUser·p0.9999: 10.907 ms/op
                 existUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399381
  mean =      2.401 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 200683 
    [ 2.500,  3.750) = 196280 
    [ 3.750,  5.000) = 1767 
    [ 5.000,  6.250) = 192 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      6.275 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  6.008 ms/op
                 getUser·p0.9999: 13.434 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.696 ms/op
                 getUser·p0.999:  9.323 ms/op
                 getUser·p0.9999: 13.158 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  6.832 ms/op
                 getUser·p0.9999: 11.026 ms/op
                 getUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390674
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 196136 
    [ 2.500,  3.750) = 191144 
    [ 3.750,  5.000) = 2570 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.558 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.804 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
Iteration   1: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 10.986 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   2: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.335 ms/op
                 listUser·p0.9999: 12.411 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   3: 2.946 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.726 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 11.123 ms/op
                 listUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323599
  mean =      2.964 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 102302 
    [ 2.500,  3.750) = 184289 
    [ 3.750,  5.000) = 30083 
    [ 5.000,  6.250) = 5512 
    [ 6.250,  7.500) = 569 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.526 ms/op
     p(99.9900) =     11.549 ms/op
     p(99.9990) =     12.641 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.710 ± 2.633  ops/ms
ClientPb.existUser                       thrpt       3  13.105 ± 1.846  ops/ms
ClientPb.getUser                         thrpt       3  13.025 ± 3.306  ops/ms
ClientPb.listUser                        thrpt       3  10.719 ± 1.353  ops/ms
ClientPb.createUser                       avgt       3   2.500 ± 0.377   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.349   ms/op
ClientPb.getUser                          avgt       3   2.488 ± 0.309   ms/op
ClientPb.listUser                         avgt       3   2.959 ± 0.360   ms/op
ClientPb.createUser                     sample  382991   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.847           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.258           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.119           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.385           ms/op
ClientPb.existUser                      sample  399381   2.401 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.908           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.275           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.942           ms/op
ClientPb.getUser                        sample  390674   2.455 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.719           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.558           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.320           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.106           ms/op
ClientPb.listUser                       sample  323599   2.964 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.526           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.549           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.714           ms/op
