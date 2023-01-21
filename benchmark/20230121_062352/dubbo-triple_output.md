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
# Warmup Iteration   1: 2.241 ops/ms
# Warmup Iteration   2: 6.332 ops/ms
# Warmup Iteration   3: 9.008 ops/ms
Iteration   1: 9.254 ops/ms
Iteration   2: 9.194 ops/ms
Iteration   3: 9.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.275 ±(99.9%) 1.710 ops/ms [Average]
  (min, avg, max) = (9.194, 9.275, 9.378), stdev = 0.094
  CI (99.9%): [7.565, 10.985] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.425 ops/ms
# Warmup Iteration   2: 8.659 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 10.029 ops/ms
Iteration   3: 9.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.844 ±(99.9%) 2.945 ops/ms [Average]
  (min, avg, max) = (9.733, 9.844, 10.029), stdev = 0.161
  CI (99.9%): [6.899, 12.789] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.226 ops/ms
# Warmup Iteration   2: 8.935 ops/ms
# Warmup Iteration   3: 8.843 ops/ms
Iteration   1: 9.037 ops/ms
Iteration   2: 9.357 ops/ms
Iteration   3: 9.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.269 ±(99.9%) 3.695 ops/ms [Average]
  (min, avg, max) = (9.037, 9.269, 9.413), stdev = 0.203
  CI (99.9%): [5.574, 12.964] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ops/ms
# Warmup Iteration   2: 7.195 ops/ms
# Warmup Iteration   3: 8.055 ops/ms
Iteration   1: 8.208 ops/ms
Iteration   2: 8.164 ops/ms
Iteration   3: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.189 ±(99.9%) 0.412 ops/ms [Average]
  (min, avg, max) = (8.164, 8.189, 8.208), stdev = 0.023
  CI (99.9%): [7.776, 8.601] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.954 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.003 ms/op
Iteration   1: 3.486 ±(99.9%) 0.006 ms/op
Iteration   2: 3.511 ±(99.9%) 0.004 ms/op
Iteration   3: 3.624 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.540 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (3.486, 3.540, 3.624), stdev = 0.074
  CI (99.9%): [2.195, 4.886] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.490 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.008 ms/op
Iteration   1: 3.267 ±(99.9%) 0.011 ms/op
Iteration   2: 3.360 ±(99.9%) 0.006 ms/op
Iteration   3: 3.309 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.312 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.267, 3.312, 3.360), stdev = 0.047
  CI (99.9%): [2.457, 4.167] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.614 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.004 ms/op
Iteration   1: 3.377 ±(99.9%) 0.010 ms/op
Iteration   2: 3.420 ±(99.9%) 0.006 ms/op
Iteration   3: 3.386 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.394 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (3.377, 3.394, 3.420), stdev = 0.023
  CI (99.9%): [2.982, 3.807] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.516 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.010 ms/op
Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
Iteration   2: 3.878 ±(99.9%) 0.012 ms/op
Iteration   3: 3.870 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.868 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (3.855, 3.868, 3.878), stdev = 0.012
  CI (99.9%): [3.655, 4.081] (assumes normal distribution)


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
# Warmup Iteration   1: 9.798 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.010 ms/op
Iteration   1: 3.425 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.392 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  20.284 ms/op
                 createUser·p0.9999: 30.199 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   2: 3.422 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  21.092 ms/op
                 createUser·p0.9999: 24.008 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   3: 3.385 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   6.140 ms/op
                 createUser·p0.999:  17.403 ms/op
                 createUser·p0.9999: 26.233 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281395
  mean =      3.411 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5035 
    [ 2.500,  5.000) = 270045 
    [ 5.000,  7.500) = 5301 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     29.314 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.991 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
Iteration   1: 3.273 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  11.063 ms/op
                 existUser·p0.9999: 21.929 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   2: 3.308 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  16.540 ms/op
                 existUser·p0.9999: 27.744 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  15.409 ms/op
                 existUser·p0.9999: 29.253 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290669
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4816 
    [ 2.500,  5.000) = 280514 
    [ 5.000,  7.500) = 4556 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     14.751 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     30.215 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.042 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.012 ms/op
Iteration   1: 3.494 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  20.513 ms/op
                 getUser·p0.9999: 22.796 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  21.686 ms/op
                 getUser·p0.9999: 24.335 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   3: 3.476 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 25.520 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277240
  mean =      3.462 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4426 
    [ 2.500,  5.000) = 264485 
    [ 5.000,  7.500) = 7371 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.247 ms/op
     p(99.9000) =     10.895 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.672 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.262 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
Iteration   1: 4.010 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  20.486 ms/op
                 listUser·p0.9999: 23.004 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.923 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 16.463 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 18.613 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241042
  mean =      3.982 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 229653 
    [ 5.000,  7.500) = 9381 
    [ 7.500, 10.000) = 1293 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     16.711 ms/op
     p(99.9900) =     21.820 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.275 ± 1.710  ops/ms
ClientPb.existUser                       thrpt       3   9.844 ± 2.945  ops/ms
ClientPb.getUser                         thrpt       3   9.269 ± 3.695  ops/ms
ClientPb.listUser                        thrpt       3   8.189 ± 0.412  ops/ms
ClientPb.createUser                       avgt       3   3.540 ± 1.345   ms/op
ClientPb.existUser                        avgt       3   3.312 ± 0.855   ms/op
ClientPb.getUser                          avgt       3   3.394 ± 0.413   ms/op
ClientPb.listUser                         avgt       3   3.868 ± 0.213   ms/op
ClientPb.createUser                     sample  281395   3.411 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.392           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.760           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.314           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.097           ms/op
ClientPb.existUser                      sample  290669   3.301 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.751           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.886           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.802           ms/op
ClientPb.getUser                        sample  277240   3.462 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.104           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.247           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.895           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.412           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.887           ms/op
ClientPb.listUser                       sample  241042   3.982 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.190           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.711           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.820           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.364           ms/op
