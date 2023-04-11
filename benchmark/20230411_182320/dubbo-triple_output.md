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
# Warmup Iteration   1: 1.577 ops/ms
# Warmup Iteration   2: 3.870 ops/ms
# Warmup Iteration   3: 7.571 ops/ms
Iteration   1: 7.512 ops/ms
Iteration   2: 7.961 ops/ms
Iteration   3: 7.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.764 ±(99.9%) 4.185 ops/ms [Average]
  (min, avg, max) = (7.512, 7.764, 7.961), stdev = 0.229
  CI (99.9%): [3.580, 11.949] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.548 ops/ms
# Warmup Iteration   2: 7.097 ops/ms
# Warmup Iteration   3: 8.394 ops/ms
Iteration   1: 8.255 ops/ms
Iteration   2: 8.527 ops/ms
Iteration   3: 7.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.226 ±(99.9%) 5.782 ops/ms [Average]
  (min, avg, max) = (7.895, 8.226, 8.527), stdev = 0.317
  CI (99.9%): [2.444, 14.007] (assumes normal distribution)


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
# Warmup Iteration   1: 2.566 ops/ms
# Warmup Iteration   2: 6.321 ops/ms
# Warmup Iteration   3: 7.198 ops/ms
Iteration   1: 8.005 ops/ms
Iteration   2: 7.834 ops/ms
Iteration   3: 8.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.985 ±(99.9%) 2.590 ops/ms [Average]
  (min, avg, max) = (7.834, 7.985, 8.116), stdev = 0.142
  CI (99.9%): [5.395, 10.576] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.401 ops/ms
# Warmup Iteration   2: 6.135 ops/ms
# Warmup Iteration   3: 6.835 ops/ms
Iteration   1: 6.677 ops/ms
Iteration   2: 6.627 ops/ms
Iteration   3: 7.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.808 ±(99.9%) 4.959 ops/ms [Average]
  (min, avg, max) = (6.627, 6.808, 7.121), stdev = 0.272
  CI (99.9%): [1.849, 11.767] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.303 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.122 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.007 ms/op
Iteration   1: 3.999 ±(99.9%) 0.007 ms/op
Iteration   2: 3.861 ±(99.9%) 0.009 ms/op
Iteration   3: 3.967 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.943 ±(99.9%) 1.317 ms/op [Average]
  (min, avg, max) = (3.861, 3.943, 3.999), stdev = 0.072
  CI (99.9%): [2.626, 5.259] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.029 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.004 ms/op
Iteration   1: 4.175 ±(99.9%) 0.005 ms/op
Iteration   2: 3.779 ±(99.9%) 0.008 ms/op
Iteration   3: 3.869 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.941 ±(99.9%) 3.784 ms/op [Average]
  (min, avg, max) = (3.779, 3.941, 4.175), stdev = 0.207
  CI (99.9%): [0.158, 7.725] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.244 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.005 ms/op
Iteration   1: 4.100 ±(99.9%) 0.007 ms/op
Iteration   2: 4.004 ±(99.9%) 0.003 ms/op
Iteration   3: 3.995 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.033 ±(99.9%) 1.065 ms/op [Average]
  (min, avg, max) = (3.995, 4.033, 4.100), stdev = 0.058
  CI (99.9%): [2.968, 5.097] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.553 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.358 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.088 ±(99.9%) 0.009 ms/op
Iteration   1: 4.658 ±(99.9%) 0.012 ms/op
Iteration   2: 4.598 ±(99.9%) 0.012 ms/op
Iteration   3: 4.425 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.560 ±(99.9%) 2.210 ms/op [Average]
  (min, avg, max) = (4.425, 4.560, 4.658), stdev = 0.121
  CI (99.9%): [2.351, 6.770] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.044 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.087 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.017 ms/op
Iteration   1: 4.016 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  11.718 ms/op
                 createUser·p0.9999: 32.768 ms/op
                 createUser·p1.00:   33.292 ms/op

Iteration   2: 3.781 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  24.688 ms/op
                 createUser·p0.9999: 28.460 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  26.660 ms/op
                 createUser·p0.9999: 30.258 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 247542
  mean =      3.878 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 399 
    [ 2.500,  5.000) = 238107 
    [ 5.000,  7.500) = 7453 
    [ 7.500, 10.000) = 1108 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.779 ms/op
     p(99.9000) =     23.590 ms/op
     p(99.9900) =     31.457 ms/op
     p(99.9990) =     33.182 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 12.785 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.010 ms/op
Iteration   1: 3.847 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.784 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  24.052 ms/op
                 existUser·p0.9999: 27.587 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   2: 3.807 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  10.519 ms/op
                 existUser·p0.9999: 27.643 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 3.737 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  25.803 ms/op
                 existUser·p0.9999: 31.046 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252635
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 476 
    [ 2.500,  5.000) = 243561 
    [ 5.000,  7.500) = 7247 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 122 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     29.712 ms/op
     p(99.9990) =     31.447 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 12.899 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.016 ms/op
Iteration   1: 3.988 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.758 ms/op
                 getUser·p0.999:  24.281 ms/op
                 getUser·p0.9999: 26.082 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   2: 4.131 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  12.827 ms/op
                 getUser·p0.9999: 27.394 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 4.148 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   7.848 ms/op
                 getUser·p0.999:  28.574 ms/op
                 getUser·p0.9999: 31.326 ms/op
                 getUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235033
  mean =      4.088 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 219471 
    [ 5.000,  7.500) = 12546 
    [ 7.500, 10.000) = 2088 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     30.622 ms/op
     p(99.9990) =     31.998 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 15.192 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.933 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.874 ±(99.9%) 0.018 ms/op
Iteration   1: 5.068 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  28.761 ms/op
                 listUser·p0.9999: 31.613 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   2: 4.641 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.235 ms/op
                 listUser·p0.999:  20.536 ms/op
                 listUser·p0.9999: 25.578 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   3: 4.639 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   9.418 ms/op
                 listUser·p0.999:  19.038 ms/op
                 listUser·p0.9999: 22.945 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200932
  mean =      4.774 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 164355 
    [ 5.000,  7.500) = 31772 
    [ 7.500, 10.000) = 2940 
    [10.000, 12.500) = 1037 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     22.383 ms/op
     p(99.9900) =     30.727 ms/op
     p(99.9990) =     31.817 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.764 ± 4.185  ops/ms
ClientPb.existUser                       thrpt       3   8.226 ± 5.782  ops/ms
ClientPb.getUser                         thrpt       3   7.985 ± 2.590  ops/ms
ClientPb.listUser                        thrpt       3   6.808 ± 4.959  ops/ms
ClientPb.createUser                       avgt       3   3.943 ± 1.317   ms/op
ClientPb.existUser                        avgt       3   3.941 ± 3.784   ms/op
ClientPb.getUser                          avgt       3   4.033 ± 1.065   ms/op
ClientPb.listUser                         avgt       3   4.560 ± 2.210   ms/op
ClientPb.createUser                     sample  247542   3.878 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.491           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.779           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.590           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.457           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  252635   3.797 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.602           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.560           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.712           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.719           ms/op
ClientPb.getUser                        sample  235033   4.088 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.198           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.379           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.622           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.260           ms/op
ClientPb.listUser                       sample  200932   4.774 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.880           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.383           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.727           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.047           ms/op
