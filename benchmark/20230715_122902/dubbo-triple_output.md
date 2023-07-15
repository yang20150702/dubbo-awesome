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
# Warmup Iteration   1: 1.287 ops/ms
# Warmup Iteration   2: 2.998 ops/ms
# Warmup Iteration   3: 6.243 ops/ms
Iteration   1: 6.551 ops/ms
Iteration   2: 6.705 ops/ms
Iteration   3: 6.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.673 ±(99.9%) 1.994 ops/ms [Average]
  (min, avg, max) = (6.551, 6.673, 6.763), stdev = 0.109
  CI (99.9%): [4.679, 8.667] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.934 ops/ms
# Warmup Iteration   2: 6.062 ops/ms
# Warmup Iteration   3: 7.023 ops/ms
Iteration   1: 6.980 ops/ms
Iteration   2: 6.961 ops/ms
Iteration   3: 6.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.978 ±(99.9%) 0.296 ops/ms [Average]
  (min, avg, max) = (6.961, 6.978, 6.993), stdev = 0.016
  CI (99.9%): [6.682, 7.274] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.914 ops/ms
# Warmup Iteration   2: 5.367 ops/ms
# Warmup Iteration   3: 6.661 ops/ms
Iteration   1: 6.773 ops/ms
Iteration   2: 7.123 ops/ms
Iteration   3: 6.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.898 ±(99.9%) 3.568 ops/ms [Average]
  (min, avg, max) = (6.773, 6.898, 7.123), stdev = 0.196
  CI (99.9%): [3.330, 10.466] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.072 ops/ms
# Warmup Iteration   2: 5.166 ops/ms
# Warmup Iteration   3: 6.248 ops/ms
Iteration   1: 5.811 ops/ms
Iteration   2: 5.963 ops/ms
Iteration   3: 5.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.882 ±(99.9%) 1.396 ops/ms [Average]
  (min, avg, max) = (5.811, 5.882, 5.963), stdev = 0.077
  CI (99.9%): [4.486, 7.279] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.595 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.136 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.634 ±(99.9%) 0.014 ms/op
Iteration   1: 4.686 ±(99.9%) 0.023 ms/op
Iteration   2: 4.910 ±(99.9%) 0.013 ms/op
Iteration   3: 4.661 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.752 ±(99.9%) 2.503 ms/op [Average]
  (min, avg, max) = (4.661, 4.752, 4.910), stdev = 0.137
  CI (99.9%): [2.250, 7.255] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.212 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.116 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.512 ±(99.9%) 0.007 ms/op
Iteration   1: 4.540 ±(99.9%) 0.011 ms/op
Iteration   2: 4.506 ±(99.9%) 0.010 ms/op
Iteration   3: 4.294 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.447 ±(99.9%) 2.431 ms/op [Average]
  (min, avg, max) = (4.294, 4.447, 4.540), stdev = 0.133
  CI (99.9%): [2.015, 6.878] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.671 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.398 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.018 ms/op
Iteration   1: 4.907 ±(99.9%) 0.012 ms/op
Iteration   2: 4.744 ±(99.9%) 0.008 ms/op
Iteration   3: 4.707 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.786 ±(99.9%) 1.938 ms/op [Average]
  (min, avg, max) = (4.707, 4.786, 4.907), stdev = 0.106
  CI (99.9%): [2.848, 6.724] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.275 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.837 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.524 ±(99.9%) 0.010 ms/op
Iteration   1: 5.368 ±(99.9%) 0.015 ms/op
Iteration   2: 5.393 ±(99.9%) 0.018 ms/op
Iteration   3: 5.365 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.375 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (5.365, 5.375, 5.393), stdev = 0.016
  CI (99.9%): [5.087, 5.663] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.053 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.304 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.206 ±(99.9%) 0.018 ms/op
Iteration   1: 4.742 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.866 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  18.498 ms/op
                 createUser·p0.9999: 24.684 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 4.759 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.036 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.775 ms/op
                 createUser·p0.95:   6.603 ms/op
                 createUser·p0.99:   8.135 ms/op
                 createUser·p0.999:  19.744 ms/op
                 createUser·p0.9999: 29.177 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   3: 4.819 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   5.767 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   8.929 ms/op
                 createUser·p0.999:  28.169 ms/op
                 createUser·p0.9999: 31.043 ms/op
                 createUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 200922
  mean =      4.773 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 166 
    [ 2.500,  5.000) = 143157 
    [ 5.000,  7.500) = 53506 
    [ 7.500, 10.000) = 3088 
    [10.000, 12.500) = 510 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.751 ms/op
     p(95.0000) =      6.390 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     22.547 ms/op
     p(99.9900) =     30.307 ms/op
     p(99.9990) =     31.848 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.508 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 4.863 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.015 ms/op
Iteration   1: 4.732 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.019 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   5.726 ms/op
                 existUser·p0.95:   6.478 ms/op
                 existUser·p0.99:   8.873 ms/op
                 existUser·p0.999:  13.648 ms/op
                 existUser·p0.9999: 22.913 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 4.587 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   5.923 ms/op
                 existUser·p0.99:   8.315 ms/op
                 existUser·p0.999:  24.411 ms/op
                 existUser·p0.9999: 33.818 ms/op
                 existUser·p1.00:   34.210 ms/op

Iteration   3: 4.495 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.167 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.915 ms/op
                 existUser·p0.99:   8.057 ms/op
                 existUser·p0.999:  15.743 ms/op
                 existUser·p0.9999: 30.692 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 208505
  mean =      4.603 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 170674 
    [ 5.000,  7.500) = 33922 
    [ 7.500, 10.000) = 2712 
    [10.000, 12.500) = 754 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     15.475 ms/op
     p(99.9900) =     31.982 ms/op
     p(99.9990) =     34.139 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.955 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.459 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.789 ±(99.9%) 0.015 ms/op
Iteration   1: 4.899 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.554 ms/op
                 getUser·p0.99:   10.754 ms/op
                 getUser·p0.999:  22.905 ms/op
                 getUser·p0.9999: 42.837 ms/op
                 getUser·p1.00:   44.368 ms/op

Iteration   2: 4.672 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.437 ms/op
                 getUser·p0.50:   4.448 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  13.730 ms/op
                 getUser·p0.9999: 28.682 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   3: 4.717 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.281 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.546 ms/op
                 getUser·p0.95:   6.136 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  14.737 ms/op
                 getUser·p0.9999: 27.376 ms/op
                 getUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 201532
  mean =      4.761 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 154297 
    [ 5.000, 10.000) = 45869 
    [10.000, 15.000) = 996 
    [15.000, 20.000) = 120 
    [20.000, 25.000) = 117 
    [25.000, 30.000) = 101 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.281 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.234 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     41.399 ms/op
     p(99.9990) =     44.036 ms/op
     p(99.9999) =     44.368 ms/op
    p(100.0000) =     44.368 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.046 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 6.437 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.349 ±(99.9%) 0.019 ms/op
Iteration   1: 5.555 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   10.311 ms/op
                 listUser·p0.999:  24.590 ms/op
                 listUser·p0.9999: 27.992 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   2: 5.449 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   6.226 ms/op
                 listUser·p0.95:   7.021 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  23.953 ms/op
                 listUser·p0.9999: 28.319 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   3: 5.368 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   10.289 ms/op
                 listUser·p0.999:  18.070 ms/op
                 listUser·p0.9999: 20.125 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 175755
  mean =      5.456 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 59626 
    [ 5.000,  7.500) = 108921 
    [ 7.500, 10.000) = 5255 
    [10.000, 12.500) = 1213 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.324 ms/op
     p(95.0000) =      7.168 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     22.749 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     29.428 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.673 ± 1.994  ops/ms
ClientPb.existUser                       thrpt       3   6.978 ± 0.296  ops/ms
ClientPb.getUser                         thrpt       3   6.898 ± 3.568  ops/ms
ClientPb.listUser                        thrpt       3   5.882 ± 1.396  ops/ms
ClientPb.createUser                       avgt       3   4.752 ± 2.503   ms/op
ClientPb.existUser                        avgt       3   4.447 ± 2.431   ms/op
ClientPb.getUser                          avgt       3   4.786 ± 1.938   ms/op
ClientPb.listUser                         avgt       3   5.375 ± 0.288   ms/op
ClientPb.createUser                     sample  200922   4.773 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.438           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.547           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.307           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  208505   4.603 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.119           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.618           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.475           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.982           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210           ms/op
ClientPb.getUser                        sample  201532   4.761 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.281           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.355           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.610           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.368           ms/op
ClientPb.listUser                       sample  175755   5.456 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.587           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.324           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.168           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.191           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.749           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.656           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
