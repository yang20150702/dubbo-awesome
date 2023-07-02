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
# Warmup Iteration   1: 0.924 ops/ms
# Warmup Iteration   2: 1.784 ops/ms
# Warmup Iteration   3: 4.166 ops/ms
Iteration   1: 4.974 ops/ms
Iteration   2: 5.112 ops/ms
Iteration   3: 5.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.047 ±(99.9%) 1.269 ops/ms [Average]
  (min, avg, max) = (4.974, 5.047, 5.112), stdev = 0.070
  CI (99.9%): [3.778, 6.317] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.353 ops/ms
# Warmup Iteration   2: 4.071 ops/ms
# Warmup Iteration   3: 5.443 ops/ms
Iteration   1: 5.545 ops/ms
Iteration   2: 5.592 ops/ms
Iteration   3: 5.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.560 ±(99.9%) 0.498 ops/ms [Average]
  (min, avg, max) = (5.544, 5.560, 5.592), stdev = 0.027
  CI (99.9%): [5.062, 6.058] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.364 ops/ms
# Warmup Iteration   2: 4.102 ops/ms
# Warmup Iteration   3: 5.082 ops/ms
Iteration   1: 5.027 ops/ms
Iteration   2: 4.853 ops/ms
Iteration   3: 5.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.998 ±(99.9%) 2.433 ops/ms [Average]
  (min, avg, max) = (4.853, 4.998, 5.114), stdev = 0.133
  CI (99.9%): [2.565, 7.431] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.457 ops/ms
# Warmup Iteration   2: 3.455 ops/ms
# Warmup Iteration   3: 4.661 ops/ms
Iteration   1: 4.556 ops/ms
Iteration   2: 4.527 ops/ms
Iteration   3: 4.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.590 ±(99.9%) 1.535 ops/ms [Average]
  (min, avg, max) = (4.527, 4.590, 4.685), stdev = 0.084
  CI (99.9%): [3.055, 6.124] (assumes normal distribution)


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
# Warmup Iteration   1: 21.174 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.774 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.062 ±(99.9%) 0.012 ms/op
Iteration   1: 6.177 ±(99.9%) 0.011 ms/op
Iteration   2: 6.094 ±(99.9%) 0.012 ms/op
Iteration   3: 6.181 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.151 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (6.094, 6.151, 6.181), stdev = 0.049
  CI (99.9%): [5.254, 7.048] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 19.290 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.145 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.888 ±(99.9%) 0.009 ms/op
Iteration   1: 5.865 ±(99.9%) 0.005 ms/op
Iteration   2: 5.681 ±(99.9%) 0.019 ms/op
Iteration   3: 5.723 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.756 ±(99.9%) 1.755 ms/op [Average]
  (min, avg, max) = (5.681, 5.756, 5.865), stdev = 0.096
  CI (99.9%): [4.001, 7.512] (assumes normal distribution)


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
# Warmup Iteration   1: 15.799 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.632 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.858 ±(99.9%) 0.014 ms/op
Iteration   1: 6.289 ±(99.9%) 0.011 ms/op
Iteration   2: 5.713 ±(99.9%) 0.016 ms/op
Iteration   3: 6.225 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.076 ±(99.9%) 5.757 ms/op [Average]
  (min, avg, max) = (5.713, 6.076, 6.289), stdev = 0.316
  CI (99.9%): [0.319, 11.833] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 23.431 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 8.385 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 6.846 ±(99.9%) 0.015 ms/op
Iteration   1: 6.814 ±(99.9%) 0.014 ms/op
Iteration   2: 6.824 ±(99.9%) 0.019 ms/op
Iteration   3: 6.756 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.798 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (6.756, 6.798, 6.824), stdev = 0.037
  CI (99.9%): [6.125, 7.470] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.952 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 9.339 ±(99.9%) 0.075 ms/op
# Warmup Iteration   3: 6.584 ±(99.9%) 0.031 ms/op
Iteration   1: 5.936 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.634 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  16.632 ms/op
                 createUser·p0.9999: 23.170 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 5.842 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.580 ms/op
                 createUser·p0.50:   5.562 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   7.823 ms/op
                 createUser·p0.99:   11.272 ms/op
                 createUser·p0.999:  25.362 ms/op
                 createUser·p0.9999: 29.842 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   3: 6.006 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.494 ms/op
                 createUser·p0.50:   5.816 ms/op
                 createUser·p0.90:   7.258 ms/op
                 createUser·p0.95:   8.221 ms/op
                 createUser·p0.99:   10.809 ms/op
                 createUser·p0.999:  24.011 ms/op
                 createUser·p0.9999: 27.569 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161847
  mean =      5.927 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 33360 
    [ 5.000,  7.500) = 115754 
    [ 7.500, 10.000) = 9913 
    [10.000, 12.500) = 1867 
    [12.500, 15.000) = 593 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.494 ms/op
     p(50.0000) =      5.677 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.176 ms/op
     p(99.0000) =     11.019 ms/op
     p(99.9000) =     21.952 ms/op
     p(99.9900) =     28.011 ms/op
     p(99.9990) =     30.874 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.990 ±(99.9%) 0.347 ms/op
# Warmup Iteration   2: 6.966 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.215 ±(99.9%) 0.023 ms/op
Iteration   1: 5.973 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.767 ms/op
                 existUser·p0.90:   7.332 ms/op
                 existUser·p0.95:   8.249 ms/op
                 existUser·p0.99:   11.354 ms/op
                 existUser·p0.999:  17.629 ms/op
                 existUser·p0.9999: 27.035 ms/op
                 existUser·p1.00:   29.229 ms/op

Iteration   2: 5.756 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.470 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   7.193 ms/op
                 existUser·p0.95:   8.356 ms/op
                 existUser·p0.99:   11.289 ms/op
                 existUser·p0.999:  24.951 ms/op
                 existUser·p0.9999: 30.315 ms/op
                 existUser·p1.00:   32.309 ms/op

Iteration   3: 6.036 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.995 ms/op
                 existUser·p0.50:   5.693 ms/op
                 existUser·p0.90:   7.635 ms/op
                 existUser·p0.95:   8.618 ms/op
                 existUser·p0.99:   11.108 ms/op
                 existUser·p0.999:  27.794 ms/op
                 existUser·p0.9999: 31.560 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 161923
  mean =      5.919 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 41619 
    [ 5.000,  7.500) = 105076 
    [ 7.500, 10.000) = 12426 
    [10.000, 12.500) = 1783 
    [12.500, 15.000) = 526 
    [15.000, 17.500) = 240 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.995 ms/op
     p(50.0000) =      5.562 ms/op
     p(90.0000) =      7.422 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     21.731 ms/op
     p(99.9900) =     31.228 ms/op
     p(99.9990) =     32.228 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 18.814 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 6.904 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.979 ±(99.9%) 0.026 ms/op
Iteration   1: 6.071 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   3.215 ms/op
                 getUser·p0.50:   5.562 ms/op
                 getUser·p0.90:   7.782 ms/op
                 getUser·p0.95:   9.011 ms/op
                 getUser·p0.99:   11.944 ms/op
                 getUser·p0.999:  28.472 ms/op
                 getUser·p0.9999: 62.063 ms/op
                 getUser·p1.00:   62.849 ms/op

Iteration   2: 5.925 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   5.603 ms/op
                 getUser·p0.90:   7.324 ms/op
                 getUser·p0.95:   8.323 ms/op
                 getUser·p0.99:   10.928 ms/op
                 getUser·p0.999:  29.665 ms/op
                 getUser·p0.9999: 34.761 ms/op
                 getUser·p1.00:   36.372 ms/op

Iteration   3: 6.060 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.712 ms/op
                 getUser·p0.50:   5.710 ms/op
                 getUser·p0.90:   7.840 ms/op
                 getUser·p0.95:   9.028 ms/op
                 getUser·p0.99:   11.321 ms/op
                 getUser·p0.999:  16.351 ms/op
                 getUser·p0.9999: 43.319 ms/op
                 getUser·p1.00:   44.171 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159434
  mean =      6.018 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 38135 
    [ 5.000, 10.000) = 117765 
    [10.000, 15.000) = 3125 
    [15.000, 20.000) = 242 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 50 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 32 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 20 
    [60.000, 65.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     11.452 ms/op
     p(99.9000) =     27.061 ms/op
     p(99.9900) =     58.932 ms/op
     p(99.9990) =     62.810 ms/op
     p(99.9999) =     62.849 ms/op
    p(100.0000) =     62.849 ms/op


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
# Warmup Iteration   1: 22.657 ±(99.9%) 0.396 ms/op
# Warmup Iteration   2: 8.732 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 7.215 ±(99.9%) 0.033 ms/op
Iteration   1: 7.072 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.753 ms/op
                 listUser·p0.50:   6.668 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.049 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  30.657 ms/op
                 listUser·p0.9999: 37.384 ms/op
                 listUser·p1.00:   37.683 ms/op

Iteration   2: 6.686 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  32.211 ms/op
                 listUser·p0.9999: 34.032 ms/op
                 listUser·p1.00:   34.669 ms/op

Iteration   3: 7.155 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.265 ms/op
                 listUser·p0.50:   6.783 ms/op
                 listUser·p0.90:   9.191 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  29.753 ms/op
                 listUser·p0.9999: 34.178 ms/op
                 listUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137834
  mean =      6.965 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2238 
    [ 5.000,  7.500) = 102507 
    [ 7.500, 10.000) = 27617 
    [10.000, 12.500) = 3986 
    [12.500, 15.000) = 873 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 129 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.753 ms/op
     p(50.0000) =      6.611 ms/op
     p(90.0000) =      8.733 ms/op
     p(95.0000) =      9.699 ms/op
     p(99.0000) =     12.632 ms/op
     p(99.9000) =     31.233 ms/op
     p(99.9900) =     35.643 ms/op
     p(99.9990) =     37.634 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.047 ± 1.269  ops/ms
ClientPb.existUser                       thrpt       3   5.560 ± 0.498  ops/ms
ClientPb.getUser                         thrpt       3   4.998 ± 2.433  ops/ms
ClientPb.listUser                        thrpt       3   4.590 ± 1.535  ops/ms
ClientPb.createUser                       avgt       3   6.151 ± 0.897   ms/op
ClientPb.existUser                        avgt       3   5.756 ± 1.755   ms/op
ClientPb.getUser                          avgt       3   6.076 ± 5.757   ms/op
ClientPb.listUser                         avgt       3   6.798 ± 0.673   ms/op
ClientPb.createUser                     sample  161847   5.927 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.494           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.242           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.176           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.019           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.952           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.011           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.097           ms/op
ClientPb.existUser                      sample  161923   5.919 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.995           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.422           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.405           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.272           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.731           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.228           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.309           ms/op
ClientPb.getUser                        sample  159434   6.018 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.034           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.847           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.452           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.061           ms/op
ClientPb.getUser:getUser·p0.9999        sample          58.932           ms/op
ClientPb.getUser:getUser·p1.00          sample          62.849           ms/op
ClientPb.listUser                       sample  137834   6.965 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.699           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.632           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.233           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.643           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.683           ms/op
