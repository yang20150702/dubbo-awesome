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
# Warmup Iteration   1: 4.959 ops/ms
# Warmup Iteration   2: 12.033 ops/ms
# Warmup Iteration   3: 12.259 ops/ms
Iteration   1: 12.513 ops/ms
Iteration   2: 12.634 ops/ms
Iteration   3: 12.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.620 ±(99.9%) 1.823 ops/ms [Average]
  (min, avg, max) = (12.513, 12.620, 12.711), stdev = 0.100
  CI (99.9%): [10.796, 14.443] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.401 ops/ms
# Warmup Iteration   2: 13.059 ops/ms
# Warmup Iteration   3: 12.933 ops/ms
Iteration   1: 13.062 ops/ms
Iteration   2: 13.087 ops/ms
Iteration   3: 12.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.032 ±(99.9%) 1.358 ops/ms [Average]
  (min, avg, max) = (12.948, 13.032, 13.087), stdev = 0.074
  CI (99.9%): [11.674, 14.391] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.797 ops/ms
# Warmup Iteration   2: 12.615 ops/ms
# Warmup Iteration   3: 12.921 ops/ms
Iteration   1: 13.019 ops/ms
Iteration   2: 12.838 ops/ms
Iteration   3: 12.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.898 ±(99.9%) 1.908 ops/ms [Average]
  (min, avg, max) = (12.838, 12.898, 13.019), stdev = 0.105
  CI (99.9%): [10.991, 14.806] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.862 ops/ms
# Warmup Iteration   2: 10.508 ops/ms
# Warmup Iteration   3: 10.754 ops/ms
Iteration   1: 10.656 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.653 ±(99.9%) 1.394 ops/ms [Average]
  (min, avg, max) = (10.575, 10.653, 10.728), stdev = 0.076
  CI (99.9%): [9.259, 12.047] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.003 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.532 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (2.527, 2.532, 2.536), stdev = 0.005
  CI (99.9%): [2.444, 2.620] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.003 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (2.447, 2.453, 2.464), stdev = 0.009
  CI (99.9%): [2.282, 2.624] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.470 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.463 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.453, 2.463, 2.470), stdev = 0.009
  CI (99.9%): [2.301, 2.626] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.624 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
Iteration   3: 3.010 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (3.002, 3.006, 3.010), stdev = 0.004
  CI (99.9%): [2.934, 3.078] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  10.944 ms/op
                 createUser·p0.9999: 13.636 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  9.455 ms/op
                 createUser·p0.9999: 12.858 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  8.724 ms/op
                 createUser·p0.9999: 11.540 ms/op
                 createUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379819
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 182781 
    [ 2.500,  3.750) = 193630 
    [ 3.750,  5.000) = 2655 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.904 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  6.598 ms/op
                 existUser·p0.9999: 13.517 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  5.045 ms/op
                 existUser·p0.9999: 14.224 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  9.101 ms/op
                 existUser·p0.9999: 12.161 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384660
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 187445 
    [ 2.500,  3.750) = 194349 
    [ 3.750,  5.000) = 2121 
    [ 5.000,  6.250) = 313 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.349 ms/op
     p(99.9900) =     13.460 ms/op
     p(99.9990) =     14.865 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  12.259 ms/op
                 getUser·p0.9999: 14.196 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 2.617 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.383 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  9.446 ms/op
                 getUser·p0.9999: 13.824 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  6.537 ms/op
                 getUser·p0.9999: 10.657 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373355
  mean =      2.569 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 180621 
    [ 2.500,  3.750) = 186131 
    [ 3.750,  5.000) = 5100 
    [ 5.000,  6.250) = 978 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      6.846 ms/op
     p(99.9900) =     13.872 ms/op
     p(99.9990) =     14.857 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.600 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.009 ms/op
Iteration   1: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.115 ms/op
                 listUser·p0.9999: 11.605 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   2: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  10.014 ms/op
                 listUser·p0.9999: 11.890 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.013 ms/op
                 listUser·p0.9999: 13.161 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319357
  mean =      3.003 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 93825 
    [ 2.500,  3.750) = 187767 
    [ 3.750,  5.000) = 30581 
    [ 5.000,  6.250) = 5839 
    [ 6.250,  7.500) = 614 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.300 ms/op
     p(99.9900) =     12.487 ms/op
     p(99.9990) =     15.228 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.620 ± 1.823  ops/ms
ClientPb.existUser                       thrpt       3  13.032 ± 1.358  ops/ms
ClientPb.getUser                         thrpt       3  12.898 ± 1.908  ops/ms
ClientPb.listUser                        thrpt       3  10.653 ± 1.394  ops/ms
ClientPb.createUser                       avgt       3   2.532 ± 0.088   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.171   ms/op
ClientPb.getUser                          avgt       3   2.463 ± 0.162   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.072   ms/op
ClientPb.createUser                     sample  379819   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.806           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.942           ms/op
ClientPb.existUser                      sample  384660   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.895           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.349           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.460           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.942           ms/op
ClientPb.getUser                        sample  373355   2.569 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.908           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.846           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.872           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.172           ms/op
ClientPb.listUser                       sample  319357   3.003 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.809           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.300           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.487           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.237           ms/op
