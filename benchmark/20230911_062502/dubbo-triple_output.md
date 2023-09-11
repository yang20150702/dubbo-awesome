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
# Warmup Iteration   1: 1.058 ops/ms
# Warmup Iteration   2: 2.447 ops/ms
# Warmup Iteration   3: 4.988 ops/ms
Iteration   1: 5.403 ops/ms
Iteration   2: 5.559 ops/ms
Iteration   3: 5.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.519 ±(99.9%) 1.864 ops/ms [Average]
  (min, avg, max) = (5.403, 5.519, 5.596), stdev = 0.102
  CI (99.9%): [3.655, 7.384] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.693 ops/ms
# Warmup Iteration   2: 4.892 ops/ms
# Warmup Iteration   3: 6.050 ops/ms
Iteration   1: 6.149 ops/ms
Iteration   2: 6.141 ops/ms
Iteration   3: 6.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.130 ±(99.9%) 0.477 ops/ms [Average]
  (min, avg, max) = (6.100, 6.130, 6.149), stdev = 0.026
  CI (99.9%): [5.653, 6.608] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.620 ops/ms
# Warmup Iteration   2: 4.217 ops/ms
# Warmup Iteration   3: 5.488 ops/ms
Iteration   1: 5.770 ops/ms
Iteration   2: 5.812 ops/ms
Iteration   3: 5.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.778 ±(99.9%) 0.557 ops/ms [Average]
  (min, avg, max) = (5.752, 5.778, 5.812), stdev = 0.031
  CI (99.9%): [5.221, 6.335] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.607 ops/ms
# Warmup Iteration   2: 4.056 ops/ms
# Warmup Iteration   3: 5.030 ops/ms
Iteration   1: 4.810 ops/ms
Iteration   2: 4.747 ops/ms
Iteration   3: 4.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.766 ±(99.9%) 0.689 ops/ms [Average]
  (min, avg, max) = (4.742, 4.766, 4.810), stdev = 0.038
  CI (99.9%): [4.077, 5.456] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.325 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 7.305 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.135 ±(99.9%) 0.011 ms/op
Iteration   1: 5.999 ±(99.9%) 0.011 ms/op
Iteration   2: 5.732 ±(99.9%) 0.011 ms/op
Iteration   3: 5.582 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.771 ±(99.9%) 3.850 ms/op [Average]
  (min, avg, max) = (5.582, 5.771, 5.999), stdev = 0.211
  CI (99.9%): [1.921, 9.620] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.518 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.354 ±(99.9%) 0.012 ms/op
Iteration   1: 5.241 ±(99.9%) 0.009 ms/op
Iteration   2: 5.277 ±(99.9%) 0.012 ms/op
Iteration   3: 5.408 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.309 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (5.241, 5.309, 5.408), stdev = 0.087
  CI (99.9%): [3.714, 6.903] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 17.771 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.426 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.633 ±(99.9%) 0.011 ms/op
Iteration   1: 5.592 ±(99.9%) 0.010 ms/op
Iteration   2: 5.734 ±(99.9%) 0.006 ms/op
Iteration   3: 5.862 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.730 ±(99.9%) 2.460 ms/op [Average]
  (min, avg, max) = (5.592, 5.730, 5.862), stdev = 0.135
  CI (99.9%): [3.270, 8.189] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 19.210 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 8.657 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.589 ±(99.9%) 0.013 ms/op
Iteration   1: 6.542 ±(99.9%) 0.014 ms/op
Iteration   2: 6.570 ±(99.9%) 0.015 ms/op
Iteration   3: 6.439 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.517 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (6.439, 6.517, 6.570), stdev = 0.069
  CI (99.9%): [5.255, 7.780] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.225 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 7.599 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 5.970 ±(99.9%) 0.027 ms/op
Iteration   1: 5.680 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.306 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   7.053 ms/op
                 createUser·p0.95:   8.487 ms/op
                 createUser·p0.99:   11.796 ms/op
                 createUser·p0.999:  19.847 ms/op
                 createUser·p0.9999: 23.965 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 5.648 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.886 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.906 ms/op
                 createUser·p0.95:   7.848 ms/op
                 createUser·p0.99:   11.551 ms/op
                 createUser·p0.999:  20.562 ms/op
                 createUser·p0.9999: 24.456 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   3: 5.400 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.817 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.398 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  20.243 ms/op
                 createUser·p0.9999: 27.268 ms/op
                 createUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172049
  mean =      5.573 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 58166 
    [ 5.000,  7.500) = 102937 
    [ 7.500, 10.000) = 7654 
    [10.000, 12.500) = 2107 
    [12.500, 15.000) = 660 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.817 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     26.437 ms/op
     p(99.9990) =     28.220 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.939 ±(99.9%) 0.453 ms/op
# Warmup Iteration   2: 6.604 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.772 ±(99.9%) 0.025 ms/op
Iteration   1: 5.527 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.150 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   6.939 ms/op
                 existUser·p0.95:   8.086 ms/op
                 existUser·p0.99:   11.530 ms/op
                 existUser·p0.999:  22.186 ms/op
                 existUser·p0.9999: 28.529 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   2: 5.415 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.978 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.610 ms/op
                 existUser·p0.99:   11.043 ms/op
                 existUser·p0.999:  26.960 ms/op
                 existUser·p0.9999: 35.985 ms/op
                 existUser·p1.00:   37.749 ms/op

Iteration   3: 5.718 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.286 ms/op
                 existUser·p0.50:   5.366 ms/op
                 existUser·p0.90:   7.430 ms/op
                 existUser·p0.95:   8.192 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  27.827 ms/op
                 existUser·p0.9999: 34.341 ms/op
                 existUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172901
  mean =      5.550 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 55681 
    [ 5.000,  7.500) = 104389 
    [ 7.500, 10.000) = 10011 
    [10.000, 12.500) = 1656 
    [12.500, 15.000) = 637 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      5.251 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      8.069 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     23.704 ms/op
     p(99.9900) =     34.518 ms/op
     p(99.9990) =     36.984 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.960 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 7.956 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 5.919 ±(99.9%) 0.025 ms/op
Iteration   1: 5.862 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.413 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.430 ms/op
                 getUser·p0.95:   8.913 ms/op
                 getUser·p0.99:   12.386 ms/op
                 getUser·p0.999:  18.430 ms/op
                 getUser·p0.9999: 26.101 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 5.780 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   7.447 ms/op
                 getUser·p0.95:   9.421 ms/op
                 getUser·p0.99:   12.730 ms/op
                 getUser·p0.999:  27.820 ms/op
                 getUser·p0.9999: 31.946 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   3: 5.569 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.576 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.849 ms/op
                 getUser·p0.95:   8.094 ms/op
                 getUser·p0.99:   10.994 ms/op
                 getUser·p0.999:  26.920 ms/op
                 getUser·p0.9999: 30.017 ms/op
                 getUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167384
  mean =      5.734 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 50089 
    [ 5.000,  7.500) = 102791 
    [ 7.500, 10.000) = 10164 
    [10.000, 12.500) = 2901 
    [12.500, 15.000) = 867 
    [15.000, 17.500) = 257 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.062 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.864 ms/op
     p(99.0000) =     12.091 ms/op
     p(99.9000) =     23.711 ms/op
     p(99.9900) =     31.041 ms/op
     p(99.9990) =     32.451 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 20.720 ±(99.9%) 0.349 ms/op
# Warmup Iteration   2: 7.641 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.522 ±(99.9%) 0.026 ms/op
Iteration   1: 6.516 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   6.062 ms/op
                 listUser·p0.90:   8.192 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   12.911 ms/op
                 listUser·p0.999:  25.129 ms/op
                 listUser·p0.9999: 31.543 ms/op
                 listUser·p1.00:   36.569 ms/op

Iteration   2: 6.569 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.953 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.200 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   11.715 ms/op
                 listUser·p0.999:  27.053 ms/op
                 listUser·p0.9999: 32.040 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   3: 6.441 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   6.087 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  22.418 ms/op
                 listUser·p0.9999: 29.231 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147465
  mean =      6.508 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 6206 
    [ 5.000,  7.500) = 119583 
    [ 7.500, 10.000) = 16189 
    [10.000, 12.500) = 4100 
    [12.500, 15.000) = 858 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.167 ms/op
     p(50.0000) =      6.111 ms/op
     p(90.0000) =      8.094 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.354 ms/op
     p(99.9000) =     25.692 ms/op
     p(99.9900) =     31.359 ms/op
     p(99.9990) =     36.258 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.519 ± 1.864  ops/ms
ClientPb.existUser                       thrpt       3   6.130 ± 0.477  ops/ms
ClientPb.getUser                         thrpt       3   5.778 ± 0.557  ops/ms
ClientPb.listUser                        thrpt       3   4.766 ± 0.689  ops/ms
ClientPb.createUser                       avgt       3   5.771 ± 3.850   ms/op
ClientPb.existUser                        avgt       3   5.309 ± 1.595   ms/op
ClientPb.getUser                          avgt       3   5.730 ± 2.460   ms/op
ClientPb.listUser                         avgt       3   6.517 ± 1.263   ms/op
ClientPb.createUser                     sample  172049   5.573 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.817           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.226           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.808           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.954           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.485           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.251           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.437           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.574           ms/op
ClientPb.existUser                      sample  172901   5.550 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.069           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.305           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.704           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.518           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.749           ms/op
ClientPb.getUser                        sample  167384   5.734 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.062           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.341           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.160           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.864           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.091           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.711           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.473           ms/op
ClientPb.listUser                       sample  147465   6.508 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.167           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.111           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.354           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.692           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.359           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.569           ms/op
