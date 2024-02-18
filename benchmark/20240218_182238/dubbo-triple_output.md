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
# Warmup Iteration   1: 5.081 ops/ms
# Warmup Iteration   2: 12.139 ops/ms
# Warmup Iteration   3: 12.222 ops/ms
Iteration   1: 12.599 ops/ms
Iteration   2: 12.642 ops/ms
Iteration   3: 12.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.679 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (12.599, 12.679, 12.797), stdev = 0.104
  CI (99.9%): [10.776, 14.583] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.937 ops/ms
# Warmup Iteration   2: 12.718 ops/ms
# Warmup Iteration   3: 12.958 ops/ms
Iteration   1: 12.871 ops/ms
Iteration   2: 12.962 ops/ms
Iteration   3: 12.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.890 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (12.839, 12.890, 12.962), stdev = 0.064
  CI (99.9%): [11.727, 14.053] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.991 ops/ms
# Warmup Iteration   2: 12.321 ops/ms
# Warmup Iteration   3: 12.563 ops/ms
Iteration   1: 12.712 ops/ms
Iteration   2: 12.682 ops/ms
Iteration   3: 12.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.686 ±(99.9%) 0.457 ops/ms [Average]
  (min, avg, max) = (12.663, 12.686, 12.712), stdev = 0.025
  CI (99.9%): [12.228, 13.143] (assumes normal distribution)


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
# Warmup Iteration   1: 6.804 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.593 ops/ms
Iteration   2: 10.711 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.633 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (10.593, 10.633, 10.711), stdev = 0.067
  CI (99.9%): [9.406, 11.859] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.003 ms/op
Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
Iteration   3: 2.525 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.525, 2.533, 2.541), stdev = 0.008
  CI (99.9%): [2.385, 2.682] (assumes normal distribution)


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.003 ms/op
Iteration   1: 2.450 ±(99.9%) 0.003 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.438, 2.456, 2.479), stdev = 0.021
  CI (99.9%): [2.071, 2.841] (assumes normal distribution)


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (2.468, 2.497, 2.518), stdev = 0.026
  CI (99.9%): [2.021, 2.973] (assumes normal distribution)


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.004 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
Iteration   3: 3.043 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (3.026, 3.035, 3.043), stdev = 0.008
  CI (99.9%): [2.883, 3.188] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.555 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  11.403 ms/op
                 createUser·p0.9999: 16.219 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  10.050 ms/op
                 createUser·p0.9999: 11.862 ms/op
                 createUser·p1.00:   11.928 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  8.167 ms/op
                 createUser·p0.9999: 10.732 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378326
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 180375 
    [ 2.500,  3.750) = 192650 
    [ 3.750,  5.000) = 3983 
    [ 5.000,  6.250) = 699 
    [ 6.250,  7.500) = 127 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     13.847 ms/op
     p(99.9990) =     16.764 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 14.169 ms/op
                 existUser·p1.00:   15.581 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 14.680 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  6.129 ms/op
                 existUser·p0.9999: 10.587 ms/op
                 existUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387491
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 191084 
    [ 2.500,  3.750) = 192426 
    [ 3.750,  5.000) = 2969 
    [ 5.000,  6.250) = 552 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      6.787 ms/op
     p(99.9900) =     14.385 ms/op
     p(99.9990) =     15.978 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  11.596 ms/op
                 getUser·p0.9999: 17.903 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.025 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.265 ms/op
                 getUser·p0.999:  9.420 ms/op
                 getUser·p0.9999: 16.482 ms/op
                 getUser·p1.00:   16.679 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  8.496 ms/op
                 getUser·p0.9999: 11.530 ms/op
                 getUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378998
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 184966 
    [ 2.500,  3.750) = 189009 
    [ 3.750,  5.000) = 3914 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 156 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     16.597 ms/op
     p(99.9990) =     18.062 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.824 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.205 ms/op
                 listUser·p0.9999: 10.977 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.668 ms/op
                 listUser·p0.9999: 13.726 ms/op
                 listUser·p1.00:   14.402 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.843 ms/op
                 listUser·p0.9999: 12.714 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316582
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 87530 
    [ 2.500,  3.750) = 188463 
    [ 3.750,  5.000) = 33113 
    [ 5.000,  6.250) = 5992 
    [ 6.250,  7.500) = 688 
    [ 7.500,  8.750) = 202 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     13.937 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.679 ± 1.904  ops/ms
ClientPb.existUser                       thrpt       3  12.890 ± 1.163  ops/ms
ClientPb.getUser                         thrpt       3  12.686 ± 0.457  ops/ms
ClientPb.listUser                        thrpt       3  10.633 ± 1.227  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.149   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.385   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.476   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.153   ms/op
ClientPb.createUser                     sample  378326   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.675           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.389           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.847           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.876           ms/op
ClientPb.existUser                      sample  387491   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.761           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.787           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.385           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.712           ms/op
ClientPb.getUser                        sample  378998   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.826           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.634           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.597           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.121           ms/op
ClientPb.listUser                       sample  316582   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.714           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.402           ms/op
