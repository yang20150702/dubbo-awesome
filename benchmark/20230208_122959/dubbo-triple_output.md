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
# Warmup Iteration   1: 1.395 ops/ms
# Warmup Iteration   2: 3.179 ops/ms
# Warmup Iteration   3: 5.747 ops/ms
Iteration   1: 5.704 ops/ms
Iteration   2: 5.994 ops/ms
Iteration   3: 6.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.918 ±(99.9%) 3.413 ops/ms [Average]
  (min, avg, max) = (5.704, 5.918, 6.054), stdev = 0.187
  CI (99.9%): [2.505, 9.330] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.960 ops/ms
# Warmup Iteration   2: 5.115 ops/ms
# Warmup Iteration   3: 5.880 ops/ms
Iteration   1: 5.707 ops/ms
Iteration   2: 5.825 ops/ms
Iteration   3: 5.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.801 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (5.707, 5.801, 5.871), stdev = 0.084
  CI (99.9%): [4.261, 7.342] (assumes normal distribution)


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
# Warmup Iteration   1: 1.331 ops/ms
# Warmup Iteration   2: 4.472 ops/ms
# Warmup Iteration   3: 5.868 ops/ms
Iteration   1: 5.813 ops/ms
Iteration   2: 5.905 ops/ms
Iteration   3: 5.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.902 ±(99.9%) 1.589 ops/ms [Average]
  (min, avg, max) = (5.813, 5.902, 5.987), stdev = 0.087
  CI (99.9%): [4.312, 7.491] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.761 ops/ms
# Warmup Iteration   2: 4.335 ops/ms
# Warmup Iteration   3: 5.451 ops/ms
Iteration   1: 5.144 ops/ms
Iteration   2: 5.308 ops/ms
Iteration   3: 5.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.168 ±(99.9%) 2.376 ops/ms [Average]
  (min, avg, max) = (5.051, 5.168, 5.308), stdev = 0.130
  CI (99.9%): [2.792, 7.544] (assumes normal distribution)


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
# Warmup Iteration   1: 16.267 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.407 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.650 ±(99.9%) 0.011 ms/op
Iteration   1: 5.663 ±(99.9%) 0.014 ms/op
Iteration   2: 5.325 ±(99.9%) 0.021 ms/op
Iteration   3: 5.507 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.499 ±(99.9%) 3.085 ms/op [Average]
  (min, avg, max) = (5.325, 5.499, 5.663), stdev = 0.169
  CI (99.9%): [2.413, 8.584] (assumes normal distribution)


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
# Warmup Iteration   1: 15.570 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.002 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.078 ±(99.9%) 0.013 ms/op
Iteration   1: 5.069 ±(99.9%) 0.008 ms/op
Iteration   2: 4.966 ±(99.9%) 0.012 ms/op
Iteration   3: 5.151 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.062 ±(99.9%) 1.691 ms/op [Average]
  (min, avg, max) = (4.966, 5.062, 5.151), stdev = 0.093
  CI (99.9%): [3.371, 6.753] (assumes normal distribution)


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
# Warmup Iteration   1: 16.133 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.567 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.464 ±(99.9%) 0.007 ms/op
Iteration   1: 5.385 ±(99.9%) 0.009 ms/op
Iteration   2: 5.252 ±(99.9%) 0.016 ms/op
Iteration   3: 5.325 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.321 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (5.252, 5.321, 5.385), stdev = 0.066
  CI (99.9%): [4.108, 6.534] (assumes normal distribution)


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
# Warmup Iteration   1: 17.382 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.031 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.983 ±(99.9%) 0.024 ms/op
Iteration   1: 5.964 ±(99.9%) 0.009 ms/op
Iteration   2: 6.181 ±(99.9%) 0.012 ms/op
Iteration   3: 5.975 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.040 ±(99.9%) 2.234 ms/op [Average]
  (min, avg, max) = (5.964, 6.040, 6.181), stdev = 0.122
  CI (99.9%): [3.807, 8.274] (assumes normal distribution)


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
# Warmup Iteration   1: 18.013 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.974 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.806 ±(99.9%) 0.026 ms/op
Iteration   1: 5.520 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   10.977 ms/op
                 createUser·p0.999:  21.629 ms/op
                 createUser·p0.9999: 28.423 ms/op
                 createUser·p1.00:   28.934 ms/op

Iteration   2: 5.107 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   4.932 ms/op
                 createUser·p0.90:   6.210 ms/op
                 createUser·p0.95:   6.832 ms/op
                 createUser·p0.99:   9.748 ms/op
                 createUser·p0.999:  26.494 ms/op
                 createUser·p0.9999: 29.488 ms/op
                 createUser·p1.00:   30.081 ms/op

Iteration   3: 5.278 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.109 ms/op
                 createUser·p0.50:   4.989 ms/op
                 createUser·p0.90:   6.472 ms/op
                 createUser·p0.95:   7.430 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  26.273 ms/op
                 createUser·p0.9999: 29.316 ms/op
                 createUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181183
  mean =      5.296 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 88004 
    [ 5.000,  7.500) = 84309 
    [ 7.500, 10.000) = 6540 
    [10.000, 12.500) = 1484 
    [12.500, 15.000) = 405 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     25.785 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     31.398 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 12.535 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.359 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.933 ±(99.9%) 0.018 ms/op
Iteration   1: 4.728 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.896 ms/op
                 existUser·p0.50:   4.538 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.226 ms/op
                 existUser·p0.99:   8.159 ms/op
                 existUser·p0.999:  21.340 ms/op
                 existUser·p0.9999: 26.804 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   2: 4.855 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.987 ms/op
                 existUser·p0.50:   4.678 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.439 ms/op
                 existUser·p0.99:   8.323 ms/op
                 existUser·p0.999:  12.763 ms/op
                 existUser·p0.9999: 25.566 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 4.733 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  14.971 ms/op
                 existUser·p0.9999: 30.350 ms/op
                 existUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 201055
  mean =      4.771 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 139 
    [ 2.500,  5.000) = 146215 
    [ 5.000,  7.500) = 50808 
    [ 7.500, 10.000) = 2964 
    [10.000, 12.500) = 565 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     14.447 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     31.159 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 13.724 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.715 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.124 ±(99.9%) 0.017 ms/op
Iteration   1: 5.123 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.302 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   6.332 ms/op
                 getUser·p0.95:   7.561 ms/op
                 getUser·p0.99:   10.830 ms/op
                 getUser·p0.999:  23.053 ms/op
                 getUser·p0.9999: 26.354 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 5.036 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   5.964 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.486 ms/op
                 getUser·p0.999:  23.781 ms/op
                 getUser·p0.9999: 31.442 ms/op
                 getUser·p1.00:   32.244 ms/op

Iteration   3: 5.091 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.800 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   6.906 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  25.936 ms/op
                 getUser·p0.9999: 31.013 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 188845
  mean =      5.083 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 112510 
    [ 5.000,  7.500) = 68584 
    [ 7.500, 10.000) = 5772 
    [10.000, 12.500) = 1236 
    [12.500, 15.000) = 374 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      7.127 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     23.079 ms/op
     p(99.9900) =     30.966 ms/op
     p(99.9990) =     32.011 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 15.764 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 6.945 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.149 ±(99.9%) 0.025 ms/op
Iteration   1: 5.749 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  24.936 ms/op
                 listUser·p0.9999: 31.926 ms/op
                 listUser·p1.00:   33.096 ms/op

Iteration   2: 5.948 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.720 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  26.350 ms/op
                 listUser·p0.9999: 32.337 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   3: 5.951 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   10.781 ms/op
                 listUser·p0.999:  19.112 ms/op
                 listUser·p0.9999: 24.056 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 163171
  mean =      5.881 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 24586 
    [ 5.000,  7.500) = 127614 
    [ 7.500, 10.000) = 8586 
    [10.000, 12.500) = 1791 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.535 ms/op
     p(99.9000) =     23.757 ms/op
     p(99.9900) =     31.693 ms/op
     p(99.9990) =     34.030 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.918 ± 3.413  ops/ms
ClientPb.existUser                       thrpt       3   5.801 ± 1.540  ops/ms
ClientPb.getUser                         thrpt       3   5.902 ± 1.589  ops/ms
ClientPb.listUser                        thrpt       3   5.168 ± 2.376  ops/ms
ClientPb.createUser                       avgt       3   5.499 ± 3.085   ms/op
ClientPb.existUser                        avgt       3   5.062 ± 1.691   ms/op
ClientPb.getUser                          avgt       3   5.321 ± 1.213   ms/op
ClientPb.listUser                         avgt       3   6.040 ± 2.234   ms/op
ClientPb.createUser                     sample  181183   5.296 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.460           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.562           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.455           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.785           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.425           ms/op
ClientPb.existUser                      sample  201055   4.771 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.618           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.571           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.324           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.487           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.447           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.705           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.195           ms/op
ClientPb.getUser                        sample  188845   5.083 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.800           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.833           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.119           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.093           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.079           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.966           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.244           ms/op
ClientPb.listUser                       sample  163171   5.881 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.710           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.020           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.535           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.757           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.693           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
