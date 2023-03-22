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
# Warmup Iteration   1: 1.491 ops/ms
# Warmup Iteration   2: 3.341 ops/ms
# Warmup Iteration   3: 6.571 ops/ms
Iteration   1: 7.530 ops/ms
Iteration   2: 6.974 ops/ms
Iteration   3: 8.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.514 ±(99.9%) 9.717 ops/ms [Average]
  (min, avg, max) = (6.974, 7.514, 8.038), stdev = 0.533
  CI (99.9%): [≈ 0, 17.231] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.180 ops/ms
# Warmup Iteration   2: 6.897 ops/ms
# Warmup Iteration   3: 7.845 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.580 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.178 ±(99.9%) 6.418 ops/ms [Average]
  (min, avg, max) = (7.925, 8.178, 8.580), stdev = 0.352
  CI (99.9%): [1.760, 14.596] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.270 ops/ms
# Warmup Iteration   2: 6.228 ops/ms
# Warmup Iteration   3: 7.801 ops/ms
Iteration   1: 7.908 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.105 ±(99.9%) 4.947 ops/ms [Average]
  (min, avg, max) = (7.908, 8.105, 8.414), stdev = 0.271
  CI (99.9%): [3.158, 13.052] (assumes normal distribution)


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
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 5.304 ops/ms
# Warmup Iteration   3: 6.704 ops/ms
Iteration   1: 6.559 ops/ms
Iteration   2: 6.935 ops/ms
Iteration   3: 6.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.757 ±(99.9%) 3.440 ops/ms [Average]
  (min, avg, max) = (6.559, 6.757, 6.935), stdev = 0.189
  CI (99.9%): [3.316, 10.197] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.412 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.813 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.006 ms/op
Iteration   1: 4.032 ±(99.9%) 0.005 ms/op
Iteration   2: 4.042 ±(99.9%) 0.009 ms/op
Iteration   3: 3.972 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.015 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.972, 4.015, 4.042), stdev = 0.038
  CI (99.9%): [3.322, 4.709] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.121 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.005 ms/op
Iteration   1: 3.876 ±(99.9%) 0.005 ms/op
Iteration   2: 4.011 ±(99.9%) 0.003 ms/op
Iteration   3: 3.911 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.933 ±(99.9%) 1.280 ms/op [Average]
  (min, avg, max) = (3.876, 3.933, 4.011), stdev = 0.070
  CI (99.9%): [2.652, 5.213] (assumes normal distribution)


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
# Warmup Iteration   1: 12.869 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.916 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.010 ms/op
Iteration   1: 4.115 ±(99.9%) 0.007 ms/op
Iteration   2: 3.949 ±(99.9%) 0.008 ms/op
Iteration   3: 3.944 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.003 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (3.944, 4.003, 4.115), stdev = 0.097
  CI (99.9%): [2.227, 5.778] (assumes normal distribution)


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
# Warmup Iteration   1: 13.249 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 6.555 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.794 ±(99.9%) 0.012 ms/op
Iteration   1: 4.734 ±(99.9%) 0.011 ms/op
Iteration   2: 4.620 ±(99.9%) 0.014 ms/op
Iteration   3: 4.605 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.653 ±(99.9%) 1.284 ms/op [Average]
  (min, avg, max) = (4.605, 4.653, 4.734), stdev = 0.070
  CI (99.9%): [3.369, 5.937] (assumes normal distribution)


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
# Warmup Iteration   1: 13.840 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 5.073 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.019 ms/op
Iteration   1: 3.993 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.305 ms/op
                 createUser·p0.999:  13.910 ms/op
                 createUser·p0.9999: 28.180 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 3.891 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.982 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  26.130 ms/op
                 createUser·p0.9999: 28.730 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   3: 3.893 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.663 ms/op
                 createUser·p0.999:  29.295 ms/op
                 createUser·p0.9999: 38.048 ms/op
                 createUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244538
  mean =      3.925 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235 
    [ 2.500,  5.000) = 234758 
    [ 5.000,  7.500) = 7753 
    [ 7.500, 10.000) = 1099 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     38.346 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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
# Warmup Iteration   1: 13.320 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.011 ms/op
Iteration   1: 3.730 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.704 ms/op
                 existUser·p0.999:  12.961 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   2: 3.794 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.790 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  25.909 ms/op
                 existUser·p0.9999: 44.733 ms/op
                 existUser·p1.00:   45.482 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.628 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  11.739 ms/op
                 existUser·p0.9999: 28.554 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251691
  mean =      3.815 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 242884 
    [ 5.000, 10.000) = 8390 
    [10.000, 15.000) = 190 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 143 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     12.719 ms/op
     p(99.9900) =     41.724 ms/op
     p(99.9990) =     45.023 ms/op
     p(99.9999) =     45.482 ms/op
    p(100.0000) =     45.482 ms/op


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
# Warmup Iteration   1: 12.121 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.810 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.015 ms/op
Iteration   1: 4.209 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   8.051 ms/op
                 getUser·p0.999:  12.173 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.942 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  11.384 ms/op
                 getUser·p0.9999: 24.798 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  24.904 ms/op
                 getUser·p0.9999: 27.788 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236971
  mean =      4.052 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 221162 
    [ 5.000,  7.500) = 13284 
    [ 7.500, 10.000) = 1906 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     26.811 ms/op
     p(99.9990) =     28.136 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 16.824 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 5.747 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.984 ±(99.9%) 0.020 ms/op
Iteration   1: 4.660 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.583 ms/op
                 listUser·p0.999:  25.965 ms/op
                 listUser·p0.9999: 27.333 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   2: 4.540 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.843 ms/op
                 listUser·p0.999:  19.386 ms/op
                 listUser·p0.9999: 42.661 ms/op
                 listUser·p1.00:   43.713 ms/op

Iteration   3: 4.625 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 22.055 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208302
  mean =      4.608 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 184629 
    [ 5.000, 10.000) = 22670 
    [10.000, 15.000) = 582 
    [15.000, 20.000) = 214 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 113 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     19.969 ms/op
     p(99.9900) =     38.669 ms/op
     p(99.9990) =     43.510 ms/op
     p(99.9999) =     43.713 ms/op
    p(100.0000) =     43.713 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.514 ± 9.717  ops/ms
ClientPb.existUser                       thrpt       3   8.178 ± 6.418  ops/ms
ClientPb.getUser                         thrpt       3   8.105 ± 4.947  ops/ms
ClientPb.listUser                        thrpt       3   6.757 ± 3.440  ops/ms
ClientPb.createUser                       avgt       3   4.015 ± 0.694   ms/op
ClientPb.existUser                        avgt       3   3.933 ± 1.280   ms/op
ClientPb.getUser                          avgt       3   4.003 ± 1.776   ms/op
ClientPb.listUser                         avgt       3   4.653 ± 1.284   ms/op
ClientPb.createUser                     sample  244538   3.925 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.412           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.110           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.797           ms/op
ClientPb.existUser                      sample  251691   3.815 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.719           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.724           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.482           ms/op
ClientPb.getUser                        sample  236971   4.052 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.520           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.206           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.811           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.967           ms/op
ClientPb.listUser                       sample  208302   4.608 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.311           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.233           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.969           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.669           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.713           ms/op
