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
# Warmup Iteration   1: 4.632 ops/ms
# Warmup Iteration   2: 11.988 ops/ms
# Warmup Iteration   3: 12.098 ops/ms
Iteration   1: 12.461 ops/ms
Iteration   2: 12.429 ops/ms
Iteration   3: 12.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.501 ±(99.9%) 1.785 ops/ms [Average]
  (min, avg, max) = (12.429, 12.501, 12.612), stdev = 0.098
  CI (99.9%): [10.716, 14.286] (assumes normal distribution)


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
# Warmup Iteration   1: 8.385 ops/ms
# Warmup Iteration   2: 12.897 ops/ms
# Warmup Iteration   3: 12.989 ops/ms
Iteration   1: 12.970 ops/ms
Iteration   2: 12.981 ops/ms
Iteration   3: 12.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.959 ±(99.9%) 0.528 ops/ms [Average]
  (min, avg, max) = (12.926, 12.959, 12.981), stdev = 0.029
  CI (99.9%): [12.431, 13.487] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.269 ops/ms
# Warmup Iteration   2: 12.629 ops/ms
# Warmup Iteration   3: 12.724 ops/ms
Iteration   1: 12.785 ops/ms
Iteration   2: 12.833 ops/ms
Iteration   3: 12.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.808 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (12.785, 12.808, 12.833), stdev = 0.024
  CI (99.9%): [12.370, 13.247] (assumes normal distribution)


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
# Warmup Iteration   1: 6.852 ops/ms
# Warmup Iteration   2: 10.455 ops/ms
# Warmup Iteration   3: 10.480 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.511 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.477 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (10.422, 10.477, 10.511), stdev = 0.048
  CI (99.9%): [9.597, 11.357] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.560 ±(99.9%) 0.005 ms/op
Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
Iteration   3: 2.563 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.567 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.560, 2.567, 2.579), stdev = 0.010
  CI (99.9%): [2.381, 2.753] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.024 ms/op [Average]
  (min, avg, max) = (2.475, 2.477, 2.478), stdev = 0.001
  CI (99.9%): [2.453, 2.500] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.528 ±(99.9%) 0.046 ms/op [Average]
  (min, avg, max) = (2.525, 2.528, 2.530), stdev = 0.003
  CI (99.9%): [2.482, 2.574] (assumes normal distribution)


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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.005 ms/op
Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
Iteration   3: 3.066 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.068 ±(99.9%) 0.078 ms/op [Average]
  (min, avg, max) = (3.065, 3.068, 3.073), stdev = 0.004
  CI (99.9%): [2.990, 3.146] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.672 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
Iteration   1: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  11.347 ms/op
                 createUser·p0.9999: 13.464 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  9.692 ms/op
                 createUser·p0.9999: 12.142 ms/op
                 createUser·p1.00:   12.435 ms/op

Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 15.254 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376626
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179973 
    [ 2.500,  5.000) = 195870 
    [ 5.000,  7.500) = 342 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      9.558 ms/op
     p(99.9900) =     14.402 ms/op
     p(99.9990) =     17.682 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.668 ms/op
                 existUser·p0.999:  7.508 ms/op
                 existUser·p0.9999: 13.177 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  6.155 ms/op
                 existUser·p0.9999: 12.847 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.868 ms/op
                 existUser·p0.9999: 11.500 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386013
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 188455 
    [ 2.500,  3.750) = 193239 
    [ 3.750,  5.000) = 3265 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      6.635 ms/op
     p(99.9900) =     12.999 ms/op
     p(99.9990) =     13.439 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
Iteration   1: 2.553 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  10.593 ms/op
                 getUser·p0.9999: 20.840 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.185 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  8.457 ms/op
                 getUser·p0.9999: 12.086 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377176
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184047 
    [ 2.500,  5.000) = 192130 
    [ 5.000,  7.500) = 601 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      8.606 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     21.160 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.009 ms/op
Iteration   1: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 10.992 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   2: 3.094 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.676 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.528 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311257
  mean =      3.082 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 77008 
    [ 2.500,  3.750) = 189842 
    [ 3.750,  5.000) = 36441 
    [ 5.000,  6.250) = 6382 
    [ 6.250,  7.500) = 765 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 322 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     12.153 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.501 ± 1.785  ops/ms
ClientPb.existUser                       thrpt       3  12.959 ± 0.528  ops/ms
ClientPb.getUser                         thrpt       3  12.808 ± 0.438  ops/ms
ClientPb.listUser                        thrpt       3  10.477 ± 0.880  ops/ms
ClientPb.createUser                       avgt       3   2.567 ± 0.186   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.024   ms/op
ClientPb.getUser                          avgt       3   2.528 ± 0.046   ms/op
ClientPb.listUser                         avgt       3   3.068 ± 0.078   ms/op
ClientPb.createUser                     sample  376626   2.546 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.691           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.558           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.218           ms/op
ClientPb.existUser                      sample  386013   2.485 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.864           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.635           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.999           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  377176   2.543 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.736           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.606           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.910           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.889           ms/op
ClientPb.listUser                       sample  311257   3.082 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.976           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.304           ms/op
