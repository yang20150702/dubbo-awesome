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
# Warmup Iteration   1: 4.828 ops/ms
# Warmup Iteration   2: 12.061 ops/ms
# Warmup Iteration   3: 12.144 ops/ms
Iteration   1: 12.383 ops/ms
Iteration   2: 12.376 ops/ms
Iteration   3: 12.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.409 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (12.376, 12.409, 12.469), stdev = 0.052
  CI (99.9%): [11.457, 13.362] (assumes normal distribution)


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
# Warmup Iteration   1: 8.082 ops/ms
# Warmup Iteration   2: 12.884 ops/ms
# Warmup Iteration   3: 12.951 ops/ms
Iteration   1: 12.988 ops/ms
Iteration   2: 13.071 ops/ms
Iteration   3: 12.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.980 ±(99.9%) 1.733 ops/ms [Average]
  (min, avg, max) = (12.882, 12.980, 13.071), stdev = 0.095
  CI (99.9%): [11.248, 14.713] (assumes normal distribution)


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
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 12.454 ops/ms
# Warmup Iteration   3: 12.716 ops/ms
Iteration   1: 12.727 ops/ms
Iteration   2: 12.549 ops/ms
Iteration   3: 12.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.599 ±(99.9%) 2.036 ops/ms [Average]
  (min, avg, max) = (12.521, 12.599, 12.727), stdev = 0.112
  CI (99.9%): [10.564, 14.635] (assumes normal distribution)


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
# Warmup Iteration   1: 6.535 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.586 ops/ms
Iteration   2: 10.465 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.535 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (10.465, 10.535, 10.586), stdev = 0.063
  CI (99.9%): [9.394, 11.676] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.207 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.004 ms/op
Iteration   1: 2.557 ±(99.9%) 0.005 ms/op
Iteration   2: 2.564 ±(99.9%) 0.003 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.556 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.547, 2.556, 2.564), stdev = 0.009
  CI (99.9%): [2.398, 2.714] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.468, 2.474, 2.479), stdev = 0.006
  CI (99.9%): [2.372, 2.576] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.522 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.519, 2.522, 2.526), stdev = 0.004
  CI (99.9%): [2.452, 2.591] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.663 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.024 ±(99.9%) 0.005 ms/op
Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
Iteration   3: 3.023 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (3.023, 3.028, 3.036), stdev = 0.007
  CI (99.9%): [2.891, 3.164] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.142 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.551 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  11.633 ms/op
                 createUser·p0.9999: 14.615 ms/op
                 createUser·p1.00:   15.548 ms/op

Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.673 ms/op
                 createUser·p0.9999: 12.976 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.948 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 10.502 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375466
  mean =      2.554 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180836 
    [ 2.500,  5.000) = 193658 
    [ 5.000,  7.500) = 529 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.120 ms/op
                 existUser·p0.9999: 13.402 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  8.740 ms/op
                 existUser·p0.9999: 12.947 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  7.578 ms/op
                 existUser·p0.9999: 12.109 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387326
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 191877 
    [ 2.500,  3.750) = 192619 
    [ 3.750,  5.000) = 2109 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      5.789 ms/op
     p(99.9900) =     12.931 ms/op
     p(99.9990) =     13.617 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 14.844 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  9.373 ms/op
                 getUser·p0.9999: 13.541 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  8.323 ms/op
                 getUser·p0.9999: 10.934 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378217
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 185190 
    [ 2.500,  3.750) = 187963 
    [ 3.750,  5.000) = 4060 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     14.385 ms/op
     p(99.9990) =     15.531 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 4.686 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.715 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 11.377 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317481
  mean =      3.021 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 87192 
    [ 2.500,  3.750) = 191261 
    [ 3.750,  5.000) = 32736 
    [ 5.000,  6.250) = 5031 
    [ 6.250,  7.500) = 464 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 227 
    [10.000, 11.250) = 172 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     17.474 ms/op
     p(99.9990) =     18.896 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.409 ± 0.952  ops/ms
ClientPb.existUser                       thrpt       3  12.980 ± 1.733  ops/ms
ClientPb.getUser                         thrpt       3  12.599 ± 2.036  ops/ms
ClientPb.listUser                        thrpt       3  10.535 ± 1.141  ops/ms
ClientPb.createUser                       avgt       3   2.556 ± 0.158   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.102   ms/op
ClientPb.getUser                          avgt       3   2.522 ± 0.069   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.137   ms/op
ClientPb.createUser                     sample  375466   2.554 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.841           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.216           ms/op
ClientPb.existUser                      sample  387326   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.812           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.789           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.931           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.763           ms/op
ClientPb.getUser                        sample  378217   2.536 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.912           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.487           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.385           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.597           ms/op
ClientPb.listUser                       sample  317481   3.021 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.456           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.474           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.038           ms/op
