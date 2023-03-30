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
# Warmup Iteration   1: 1.671 ops/ms
# Warmup Iteration   2: 3.508 ops/ms
# Warmup Iteration   3: 6.620 ops/ms
Iteration   1: 7.301 ops/ms
Iteration   2: 7.965 ops/ms
Iteration   3: 7.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.623 ±(99.9%) 6.065 ops/ms [Average]
  (min, avg, max) = (7.301, 7.623, 7.965), stdev = 0.332
  CI (99.9%): [1.558, 13.689] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.441 ops/ms
# Warmup Iteration   2: 6.470 ops/ms
# Warmup Iteration   3: 7.939 ops/ms
Iteration   1: 8.242 ops/ms
Iteration   2: 7.854 ops/ms
Iteration   3: 7.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.008 ±(99.9%) 3.756 ops/ms [Average]
  (min, avg, max) = (7.854, 8.008, 8.242), stdev = 0.206
  CI (99.9%): [4.252, 11.764] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.172 ops/ms
# Warmup Iteration   2: 6.366 ops/ms
# Warmup Iteration   3: 7.365 ops/ms
Iteration   1: 7.678 ops/ms
Iteration   2: 7.639 ops/ms
Iteration   3: 8.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.793 ±(99.9%) 4.277 ops/ms [Average]
  (min, avg, max) = (7.639, 7.793, 8.063), stdev = 0.234
  CI (99.9%): [3.516, 12.070] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.971 ops/ms
# Warmup Iteration   2: 5.574 ops/ms
# Warmup Iteration   3: 6.310 ops/ms
Iteration   1: 6.663 ops/ms
Iteration   2: 6.555 ops/ms
Iteration   3: 6.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.586 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (6.542, 6.586, 6.663), stdev = 0.066
  CI (99.9%): [5.375, 7.798] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 15.169 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.671 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.013 ms/op
Iteration   1: 4.269 ±(99.9%) 0.006 ms/op
Iteration   2: 3.994 ±(99.9%) 0.015 ms/op
Iteration   3: 4.180 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.148 ±(99.9%) 2.564 ms/op [Average]
  (min, avg, max) = (3.994, 4.148, 4.269), stdev = 0.141
  CI (99.9%): [1.584, 6.712] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.318 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.831 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.006 ms/op
Iteration   1: 3.858 ±(99.9%) 0.011 ms/op
Iteration   2: 3.894 ±(99.9%) 0.006 ms/op
Iteration   3: 3.816 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.856 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.816, 3.856, 3.894), stdev = 0.039
  CI (99.9%): [3.141, 4.571] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 13.486 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.005 ms/op
Iteration   1: 4.181 ±(99.9%) 0.004 ms/op
Iteration   2: 4.036 ±(99.9%) 0.011 ms/op
Iteration   3: 3.876 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.031 ±(99.9%) 2.777 ms/op [Average]
  (min, avg, max) = (3.876, 4.031, 4.181), stdev = 0.152
  CI (99.9%): [1.254, 6.808] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.839 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.740 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.924 ±(99.9%) 0.012 ms/op
Iteration   1: 4.556 ±(99.9%) 0.018 ms/op
Iteration   2: 4.644 ±(99.9%) 0.014 ms/op
Iteration   3: 4.613 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.604 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (4.556, 4.604, 4.644), stdev = 0.045
  CI (99.9%): [3.786, 5.423] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.244 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.894 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.741 ±(99.9%) 0.021 ms/op
Iteration   1: 4.103 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.048 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.597 ms/op
                 createUser·p0.999:  14.975 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 4.139 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.968 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  23.619 ms/op
                 createUser·p0.9999: 29.065 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   3: 4.320 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   4.061 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.021 ms/op
                 createUser·p0.99:   8.061 ms/op
                 createUser·p0.999:  13.090 ms/op
                 createUser·p0.9999: 29.562 ms/op
                 createUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229207
  mean =      4.185 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 320 
    [ 2.500,  5.000) = 207691 
    [ 5.000,  7.500) = 18643 
    [ 7.500, 10.000) = 1789 
    [10.000, 12.500) = 385 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     28.609 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.368 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.014 ms/op
Iteration   1: 4.074 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  11.746 ms/op
                 existUser·p0.9999: 31.462 ms/op
                 existUser·p1.00:   32.047 ms/op

Iteration   2: 3.918 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.843 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  11.225 ms/op
                 existUser·p0.9999: 27.930 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.906 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  29.400 ms/op
                 existUser·p0.9999: 37.845 ms/op
                 existUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241931
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 240 
    [ 2.500,  5.000) = 228842 
    [ 5.000,  7.500) = 10851 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 78 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     12.524 ms/op
     p(99.9900) =     35.704 ms/op
     p(99.9990) =     38.508 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 11.987 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 5.175 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.012 ms/op
Iteration   1: 4.336 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.003 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  25.599 ms/op
                 getUser·p0.9999: 29.592 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   2: 4.177 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.265 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.643 ms/op
                 getUser·p0.999:  16.122 ms/op
                 getUser·p0.9999: 34.210 ms/op
                 getUser·p1.00:   35.062 ms/op

Iteration   3: 4.159 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.122 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   7.700 ms/op
                 getUser·p0.999:  12.501 ms/op
                 getUser·p0.9999: 30.814 ms/op
                 getUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 227342
  mean =      4.222 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 207989 
    [ 5.000,  7.500) = 16707 
    [ 7.500, 10.000) = 1804 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 105 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     32.506 ms/op
     p(99.9990) =     35.044 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 16.579 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 6.320 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.184 ±(99.9%) 0.020 ms/op
Iteration   1: 5.079 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   7.741 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  25.492 ms/op
                 listUser·p0.9999: 32.475 ms/op
                 listUser·p1.00:   33.358 ms/op

Iteration   2: 4.756 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   8.579 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 25.127 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   3: 4.745 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.217 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  18.448 ms/op
                 listUser·p0.9999: 21.701 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197632
  mean =      4.856 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 157347 
    [ 5.000,  7.500) = 33291 
    [ 7.500, 10.000) = 5245 
    [10.000, 12.500) = 1066 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.040 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.701 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     20.352 ms/op
     p(99.9900) =     30.276 ms/op
     p(99.9990) =     33.262 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.623 ± 6.065  ops/ms
ClientPb.existUser                       thrpt       3   8.008 ± 3.756  ops/ms
ClientPb.getUser                         thrpt       3   7.793 ± 4.277  ops/ms
ClientPb.listUser                        thrpt       3   6.586 ± 1.212  ops/ms
ClientPb.createUser                       avgt       3   4.148 ± 2.564   ms/op
ClientPb.existUser                        avgt       3   3.856 ± 0.715   ms/op
ClientPb.getUser                          avgt       3   4.031 ± 2.777   ms/op
ClientPb.listUser                         avgt       3   4.604 ± 0.819   ms/op
ClientPb.createUser                     sample  229207   4.185 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.741           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.891           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.609           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.441           ms/op
ClientPb.existUser                      sample  241931   3.965 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.511           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.054           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.524           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.704           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.059           ms/op
ClientPb.getUser                        sample  227342   4.222 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.003           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.571           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.668           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.506           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.062           ms/op
ClientPb.listUser                       sample  197632   4.856 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.040           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.276           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.358           ms/op
