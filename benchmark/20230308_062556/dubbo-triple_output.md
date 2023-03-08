# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.731 ops/ms
# Warmup Iteration   2: 3.917 ops/ms
# Warmup Iteration   3: 7.436 ops/ms
Iteration   1: 7.595 ops/ms
Iteration   2: 8.258 ops/ms
Iteration   3: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.046 ±(99.9%) 7.136 ops/ms [Average]
  (min, avg, max) = (7.595, 8.046, 8.286), stdev = 0.391
  CI (99.9%): [0.910, 15.182] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.480 ops/ms
# Warmup Iteration   2: 7.198 ops/ms
# Warmup Iteration   3: 8.137 ops/ms
Iteration   1: 8.296 ops/ms
Iteration   2: 8.609 ops/ms
Iteration   3: 8.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.556 ±(99.9%) 4.338 ops/ms [Average]
  (min, avg, max) = (8.296, 8.556, 8.763), stdev = 0.238
  CI (99.9%): [4.218, 12.894] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 6.575 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 8.036 ops/ms
Iteration   2: 8.165 ops/ms
Iteration   3: 8.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.095 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (8.036, 8.095, 8.165), stdev = 0.065
  CI (99.9%): [6.903, 9.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.441 ops/ms
# Warmup Iteration   2: 6.243 ops/ms
# Warmup Iteration   3: 6.783 ops/ms
Iteration   1: 7.084 ops/ms
Iteration   2: 6.858 ops/ms
Iteration   3: 7.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.992 ±(99.9%) 2.172 ops/ms [Average]
  (min, avg, max) = (6.858, 6.992, 7.084), stdev = 0.119
  CI (99.9%): [4.820, 9.165] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.397 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.576 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.420 ±(99.9%) 0.008 ms/op
Iteration   1: 4.053 ±(99.9%) 0.004 ms/op
Iteration   2: 4.087 ±(99.9%) 0.008 ms/op
Iteration   3: 4.027 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.056 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (4.027, 4.056, 4.087), stdev = 0.030
  CI (99.9%): [3.504, 4.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.269 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.005 ms/op
Iteration   1: 3.945 ±(99.9%) 0.010 ms/op
Iteration   2: 3.871 ±(99.9%) 0.011 ms/op
Iteration   3: 3.788 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.868 ±(99.9%) 1.434 ms/op [Average]
  (min, avg, max) = (3.788, 3.868, 3.945), stdev = 0.079
  CI (99.9%): [2.434, 5.302] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.079 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.840 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.005 ms/op
Iteration   1: 3.869 ±(99.9%) 0.004 ms/op
Iteration   2: 3.979 ±(99.9%) 0.009 ms/op
Iteration   3: 3.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.939 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (3.869, 3.939, 3.979), stdev = 0.061
  CI (99.9%): [2.831, 5.047] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.657 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.193 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.762 ±(99.9%) 0.009 ms/op
Iteration   1: 4.687 ±(99.9%) 0.011 ms/op
Iteration   2: 4.536 ±(99.9%) 0.009 ms/op
Iteration   3: 4.613 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.612 ±(99.9%) 1.376 ms/op [Average]
  (min, avg, max) = (4.536, 4.612, 4.687), stdev = 0.075
  CI (99.9%): [3.236, 5.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.143 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.018 ms/op
Iteration   1: 3.889 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.286 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  15.758 ms/op
                 createUser·p0.9999: 28.322 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   2: 4.038 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  25.477 ms/op
                 createUser·p0.9999: 27.069 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   3: 3.981 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  8.421 ms/op
                 createUser·p0.9999: 41.157 ms/op
                 createUser·p1.00:   42.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241780
  mean =      3.968 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 230885 
    [ 5.000, 10.000) = 10418 
    [10.000, 15.000) = 221 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 161 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     40.436 ms/op
     p(99.9990) =     41.730 ms/op
     p(99.9999) =     42.074 ms/op
    p(100.0000) =     42.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.186 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.011 ms/op
Iteration   1: 3.777 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.884 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 26.937 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   2: 4.046 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  14.251 ms/op
                 existUser·p0.9999: 26.971 ms/op
                 existUser·p1.00:   29.786 ms/op

Iteration   3: 3.820 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.889 ms/op
                 existUser·p0.999:  23.849 ms/op
                 existUser·p0.9999: 27.235 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247547
  mean =      3.877 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 300 
    [ 2.500,  5.000) = 237459 
    [ 5.000,  7.500) = 7119 
    [ 7.500, 10.000) = 1714 
    [10.000, 12.500) = 653 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 82 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     14.089 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     29.594 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.567 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
Iteration   1: 3.952 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.963 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  20.250 ms/op
                 getUser·p0.9999: 22.915 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.843 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.339 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   5.935 ms/op
                 getUser·p0.999:  13.682 ms/op
                 getUser·p0.9999: 24.696 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   3: 3.956 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  26.320 ms/op
                 getUser·p0.9999: 32.846 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245339
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 235195 
    [ 5.000,  7.500) = 7801 
    [ 7.500, 10.000) = 1542 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     20.141 ms/op
     p(99.9900) =     31.057 ms/op
     p(99.9990) =     33.590 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.466 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.805 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.863 ±(99.9%) 0.017 ms/op
Iteration   1: 4.955 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.060 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  23.305 ms/op
                 listUser·p0.9999: 27.425 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 4.708 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 21.313 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 4.752 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  16.878 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199726
  mean =      4.803 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 163595 
    [ 5.000,  7.500) = 29482 
    [ 7.500, 10.000) = 5225 
    [10.000, 12.500) = 811 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.995 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      9.433 ms/op
     p(99.9000) =     19.604 ms/op
     p(99.9900) =     25.594 ms/op
     p(99.9990) =     30.213 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.046 ± 7.136  ops/ms
ClientPb.existUser                       thrpt       3   8.556 ± 4.338  ops/ms
ClientPb.getUser                         thrpt       3   8.095 ± 1.192  ops/ms
ClientPb.listUser                        thrpt       3   6.992 ± 2.172  ops/ms
ClientPb.createUser                       avgt       3   4.056 ± 0.552   ms/op
ClientPb.existUser                        avgt       3   3.868 ± 1.434   ms/op
ClientPb.getUser                          avgt       3   3.939 ± 1.108   ms/op
ClientPb.listUser                         avgt       3   4.612 ± 1.376   ms/op
ClientPb.createUser                     sample  241780   3.968 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.702           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.676           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.761           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.436           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.074           ms/op
ClientPb.existUser                      sample  247547   3.877 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.487           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.627           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.089           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.968           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.786           ms/op
ClientPb.getUser                        sample  245339   3.916 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.291           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.141           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.057           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  199726   4.803 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.995           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.226           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.939           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.433           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.604           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.594           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.409           ms/op
