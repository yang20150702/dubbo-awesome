# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.538 ops/ms
# Warmup Iteration   2: 3.668 ops/ms
# Warmup Iteration   3: 7.196 ops/ms
Iteration   1: 7.285 ops/ms
Iteration   2: 7.944 ops/ms
Iteration   3: 7.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.619 ±(99.9%) 6.019 ops/ms [Average]
  (min, avg, max) = (7.285, 7.619, 7.944), stdev = 0.330
  CI (99.9%): [1.600, 13.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.315 ops/ms
# Warmup Iteration   2: 6.897 ops/ms
# Warmup Iteration   3: 7.896 ops/ms
Iteration   1: 7.536 ops/ms
Iteration   2: 8.365 ops/ms
Iteration   3: 8.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.108 ±(99.9%) 9.047 ops/ms [Average]
  (min, avg, max) = (7.536, 8.108, 8.423), stdev = 0.496
  CI (99.9%): [≈ 0, 17.155] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.087 ops/ms
# Warmup Iteration   2: 6.400 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 7.594 ops/ms
Iteration   2: 7.691 ops/ms
Iteration   3: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.795 ±(99.9%) 4.901 ops/ms [Average]
  (min, avg, max) = (7.594, 7.795, 8.100), stdev = 0.269
  CI (99.9%): [2.894, 12.696] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.187 ops/ms
# Warmup Iteration   2: 6.048 ops/ms
# Warmup Iteration   3: 6.469 ops/ms
Iteration   1: 6.844 ops/ms
Iteration   2: 6.943 ops/ms
Iteration   3: 6.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.833 ±(99.9%) 2.105 ops/ms [Average]
  (min, avg, max) = (6.713, 6.833, 6.943), stdev = 0.115
  CI (99.9%): [4.729, 8.938] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.749 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.011 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.008 ms/op
Iteration   1: 4.050 ±(99.9%) 0.004 ms/op
Iteration   2: 3.999 ±(99.9%) 0.006 ms/op
Iteration   3: 4.167 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.072 ±(99.9%) 1.575 ms/op [Average]
  (min, avg, max) = (3.999, 4.072, 4.167), stdev = 0.086
  CI (99.9%): [2.497, 5.647] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.349 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.375 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.006 ms/op
Iteration   1: 3.914 ±(99.9%) 0.004 ms/op
Iteration   2: 3.886 ±(99.9%) 0.004 ms/op
Iteration   3: 3.858 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.886 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.858, 3.886, 3.914), stdev = 0.028
  CI (99.9%): [3.373, 4.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.229 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.005 ms/op
Iteration   1: 4.102 ±(99.9%) 0.010 ms/op
Iteration   2: 4.019 ±(99.9%) 0.005 ms/op
Iteration   3: 3.899 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.006 ±(99.9%) 1.863 ms/op [Average]
  (min, avg, max) = (3.899, 4.006, 4.102), stdev = 0.102
  CI (99.9%): [2.143, 5.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.176 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.754 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.904 ±(99.9%) 0.009 ms/op
Iteration   1: 4.853 ±(99.9%) 0.009 ms/op
Iteration   2: 4.766 ±(99.9%) 0.012 ms/op
Iteration   3: 4.766 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.795 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (4.766, 4.795, 4.853), stdev = 0.050
  CI (99.9%): [3.880, 5.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.947 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.043 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.390 ±(99.9%) 0.018 ms/op
Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  23.527 ms/op
                 createUser·p0.9999: 26.144 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   2: 3.984 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  25.634 ms/op
                 createUser·p0.9999: 29.557 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   3: 4.014 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.692 ms/op
                 createUser·p0.999:  28.586 ms/op
                 createUser·p0.9999: 37.618 ms/op
                 createUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240316
  mean =      3.991 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 385 
    [ 2.500,  5.000) = 228332 
    [ 5.000,  7.500) = 9242 
    [ 7.500, 10.000) = 1648 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     24.303 ms/op
     p(99.9900) =     35.387 ms/op
     p(99.9990) =     37.866 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.811 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.092 ±(99.9%) 0.014 ms/op
Iteration   1: 4.114 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.874 ms/op
                 existUser·p0.99:   8.684 ms/op
                 existUser·p0.999:  22.275 ms/op
                 existUser·p0.9999: 28.457 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   2: 3.898 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.512 ms/op
                 existUser·p0.999:  15.332 ms/op
                 existUser·p0.9999: 30.042 ms/op
                 existUser·p1.00:   30.376 ms/op

Iteration   3: 4.037 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   7.478 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 35.526 ms/op
                 existUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239005
  mean =      4.014 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180 
    [ 2.500,  5.000) = 223376 
    [ 5.000,  7.500) = 12128 
    [ 7.500, 10.000) = 2451 
    [10.000, 12.500) = 431 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     35.931 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.722 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.870 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.013 ms/op
Iteration   1: 4.178 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   6.529 ms/op
                 getUser·p0.99:   9.638 ms/op
                 getUser·p0.999:  23.309 ms/op
                 getUser·p0.9999: 26.171 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   2: 4.020 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.255 ms/op
                 getUser·p0.999:  13.563 ms/op
                 getUser·p0.9999: 27.723 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   3: 4.026 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   8.233 ms/op
                 getUser·p0.999:  29.702 ms/op
                 getUser·p0.9999: 33.397 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235609
  mean =      4.074 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 219923 
    [ 5.000,  7.500) = 11277 
    [ 7.500, 10.000) = 3114 
    [10.000, 12.500) = 779 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     23.356 ms/op
     p(99.9900) =     32.090 ms/op
     p(99.9990) =     33.985 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.935 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 6.060 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.058 ±(99.9%) 0.020 ms/op
Iteration   1: 4.683 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.054 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  22.656 ms/op
                 listUser·p0.9999: 27.760 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   2: 4.858 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.707 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   9.991 ms/op
                 listUser·p0.999:  19.601 ms/op
                 listUser·p0.9999: 24.407 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 4.715 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   9.019 ms/op
                 listUser·p0.999:  16.339 ms/op
                 listUser·p0.9999: 18.070 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201847
  mean =      4.751 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 167846 
    [ 5.000,  7.500) = 28678 
    [ 7.500, 10.000) = 3692 
    [10.000, 12.500) = 1036 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.007 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     26.235 ms/op
     p(99.9990) =     28.504 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.619 ± 6.019  ops/ms
ClientPb.existUser                       thrpt       3   8.108 ± 9.047  ops/ms
ClientPb.getUser                         thrpt       3   7.795 ± 4.901  ops/ms
ClientPb.listUser                        thrpt       3   6.833 ± 2.105  ops/ms
ClientPb.createUser                       avgt       3   4.072 ± 1.575   ms/op
ClientPb.existUser                        avgt       3   3.886 ± 0.514   ms/op
ClientPb.getUser                          avgt       3   4.006 ± 1.863   ms/op
ClientPb.listUser                         avgt       3   4.795 ± 0.915   ms/op
ClientPb.createUser                     sample  240316   3.991 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.423           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.303           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.387           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.601           ms/op
ClientPb.existUser                      sample  239005   4.014 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.362           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.102           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.187           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.487           ms/op
ClientPb.getUser                        sample  235609   4.074 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.198           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.356           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.090           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  201847   4.751 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.007           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.104           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.917           ms/op
