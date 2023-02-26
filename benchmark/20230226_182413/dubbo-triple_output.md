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
# Warmup Iteration   1: 1.082 ops/ms
# Warmup Iteration   2: 2.411 ops/ms
# Warmup Iteration   3: 5.565 ops/ms
Iteration   1: 5.784 ops/ms
Iteration   2: 5.979 ops/ms
Iteration   3: 5.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.849 ±(99.9%) 2.050 ops/ms [Average]
  (min, avg, max) = (5.784, 5.849, 5.979), stdev = 0.112
  CI (99.9%): [3.800, 7.899] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.714 ops/ms
# Warmup Iteration   2: 5.092 ops/ms
# Warmup Iteration   3: 6.364 ops/ms
Iteration   1: 6.295 ops/ms
Iteration   2: 6.215 ops/ms
Iteration   3: 6.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.265 ±(99.9%) 0.795 ops/ms [Average]
  (min, avg, max) = (6.215, 6.265, 6.295), stdev = 0.044
  CI (99.9%): [5.470, 7.060] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.766 ops/ms
# Warmup Iteration   2: 4.898 ops/ms
# Warmup Iteration   3: 5.794 ops/ms
Iteration   1: 5.810 ops/ms
Iteration   2: 5.875 ops/ms
Iteration   3: 6.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.908 ±(99.9%) 2.146 ops/ms [Average]
  (min, avg, max) = (5.810, 5.908, 6.038), stdev = 0.118
  CI (99.9%): [3.762, 8.053] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.655 ops/ms
# Warmup Iteration   2: 4.140 ops/ms
# Warmup Iteration   3: 5.158 ops/ms
Iteration   1: 4.918 ops/ms
Iteration   2: 5.059 ops/ms
Iteration   3: 5.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.134 ±(99.9%) 4.783 ops/ms [Average]
  (min, avg, max) = (4.918, 5.134, 5.426), stdev = 0.262
  CI (99.9%): [0.351, 9.918] (assumes normal distribution)


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
# Warmup Iteration   1: 17.953 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.073 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.700 ±(99.9%) 0.010 ms/op
Iteration   1: 5.334 ±(99.9%) 0.012 ms/op
Iteration   2: 5.245 ±(99.9%) 0.009 ms/op
Iteration   3: 5.314 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.297 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (5.245, 5.297, 5.334), stdev = 0.047
  CI (99.9%): [4.447, 6.148] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.562 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.104 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.404 ±(99.9%) 0.009 ms/op
Iteration   1: 4.915 ±(99.9%) 0.009 ms/op
Iteration   2: 4.816 ±(99.9%) 0.012 ms/op
Iteration   3: 4.924 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.885 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (4.816, 4.885, 4.924), stdev = 0.060
  CI (99.9%): [3.788, 5.981] (assumes normal distribution)


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
# Warmup Iteration   1: 17.971 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.171 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.301 ±(99.9%) 0.007 ms/op
Iteration   1: 5.340 ±(99.9%) 0.010 ms/op
Iteration   2: 5.084 ±(99.9%) 0.011 ms/op
Iteration   3: 5.158 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.194 ±(99.9%) 2.400 ms/op [Average]
  (min, avg, max) = (5.084, 5.194, 5.340), stdev = 0.132
  CI (99.9%): [2.794, 7.594] (assumes normal distribution)


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
# Warmup Iteration   1: 20.357 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.896 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.227 ±(99.9%) 0.013 ms/op
Iteration   1: 6.290 ±(99.9%) 0.012 ms/op
Iteration   2: 6.020 ±(99.9%) 0.010 ms/op
Iteration   3: 5.970 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.094 ±(99.9%) 3.140 ms/op [Average]
  (min, avg, max) = (5.970, 6.094, 6.290), stdev = 0.172
  CI (99.9%): [2.953, 9.234] (assumes normal distribution)


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
# Warmup Iteration   1: 18.803 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 7.178 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.547 ±(99.9%) 0.024 ms/op
Iteration   1: 5.083 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.470 ms/op
                 createUser·p0.50:   4.727 ms/op
                 createUser·p0.90:   6.226 ms/op
                 createUser·p0.95:   7.037 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  21.663 ms/op
                 createUser·p0.9999: 25.653 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 5.161 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   4.817 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   7.264 ms/op
                 createUser·p0.99:   10.781 ms/op
                 createUser·p0.999:  25.006 ms/op
                 createUser·p0.9999: 28.496 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 5.242 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   10.961 ms/op
                 createUser·p0.999:  26.349 ms/op
                 createUser·p0.9999: 34.400 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185791
  mean =      5.161 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 111688 
    [ 5.000,  7.500) = 65620 
    [ 7.500, 10.000) = 6032 
    [10.000, 12.500) = 1441 
    [12.500, 15.000) = 488 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     22.951 ms/op
     p(99.9900) =     32.421 ms/op
     p(99.9990) =     35.633 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 15.848 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.465 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.140 ±(99.9%) 0.019 ms/op
Iteration   1: 4.975 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   6.087 ms/op
                 existUser·p0.95:   7.315 ms/op
                 existUser·p0.99:   10.109 ms/op
                 existUser·p0.999:  23.676 ms/op
                 existUser·p0.9999: 33.863 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   2: 4.979 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   4.628 ms/op
                 existUser·p0.90:   6.177 ms/op
                 existUser·p0.95:   7.266 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  23.632 ms/op
                 existUser·p0.9999: 27.366 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 5.160 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.896 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.406 ms/op
                 existUser·p0.95:   7.487 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  15.019 ms/op
                 existUser·p0.9999: 30.468 ms/op
                 existUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190515
  mean =      5.037 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 127860 
    [ 5.000,  7.500) = 53985 
    [ 7.500, 10.000) = 6682 
    [10.000, 12.500) = 1310 
    [12.500, 15.000) = 371 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      7.356 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     30.441 ms/op
     p(99.9990) =     34.693 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 16.931 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 6.043 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.362 ±(99.9%) 0.020 ms/op
Iteration   1: 5.464 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   7.356 ms/op
                 getUser·p0.95:   9.028 ms/op
                 getUser·p0.99:   13.926 ms/op
                 getUser·p0.999:  25.737 ms/op
                 getUser·p0.9999: 27.469 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   2: 5.396 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.232 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   8.274 ms/op
                 getUser·p0.99:   11.583 ms/op
                 getUser·p0.999:  30.359 ms/op
                 getUser·p0.9999: 33.559 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 5.176 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  25.858 ms/op
                 getUser·p0.9999: 30.992 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179555
  mean =      5.343 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 99718 
    [ 5.000,  7.500) = 67111 
    [ 7.500, 10.000) = 8773 
    [10.000, 12.500) = 2263 
    [12.500, 15.000) = 936 
    [15.000, 17.500) = 256 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     26.575 ms/op
     p(99.9900) =     33.292 ms/op
     p(99.9990) =     34.027 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 19.757 ±(99.9%) 0.340 ms/op
# Warmup Iteration   2: 7.576 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.671 ±(99.9%) 0.030 ms/op
Iteration   1: 6.508 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   14.025 ms/op
                 listUser·p0.999:  26.801 ms/op
                 listUser·p0.9999: 30.349 ms/op
                 listUser·p1.00:   32.834 ms/op

Iteration   2: 6.451 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  30.357 ms/op
                 listUser·p0.9999: 38.541 ms/op
                 listUser·p1.00:   39.191 ms/op

Iteration   3: 6.106 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.817 ms/op
                 listUser·p0.50:   5.710 ms/op
                 listUser·p0.90:   7.340 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  27.023 ms/op
                 listUser·p0.9999: 30.893 ms/op
                 listUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151000
  mean =      6.350 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 7787 
    [ 5.000,  7.500) = 123475 
    [ 7.500, 10.000) = 14554 
    [10.000, 12.500) = 3598 
    [12.500, 15.000) = 972 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      5.890 ms/op
     p(90.0000) =      7.995 ms/op
     p(95.0000) =      9.290 ms/op
     p(99.0000) =     12.616 ms/op
     p(99.9000) =     27.492 ms/op
     p(99.9900) =     37.605 ms/op
     p(99.9990) =     39.157 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.849 ± 2.050  ops/ms
ClientPb.existUser                       thrpt       3   6.265 ± 0.795  ops/ms
ClientPb.getUser                         thrpt       3   5.908 ± 2.146  ops/ms
ClientPb.listUser                        thrpt       3   5.134 ± 4.783  ops/ms
ClientPb.createUser                       avgt       3   5.297 ± 0.851   ms/op
ClientPb.existUser                        avgt       3   4.885 ± 1.096   ms/op
ClientPb.getUser                          avgt       3   5.194 ± 2.400   ms/op
ClientPb.listUser                         avgt       3   6.094 ± 3.140   ms/op
ClientPb.createUser                     sample  185791   5.161 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.470           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.792           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.357           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.951           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.421           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  190515   5.037 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.407           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.356           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.027           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.350           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.441           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  179555   5.343 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.540           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.184           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.272           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.575           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.292           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  151000   6.350 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.817           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.890           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.995           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.290           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.616           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.492           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.605           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.191           ms/op
