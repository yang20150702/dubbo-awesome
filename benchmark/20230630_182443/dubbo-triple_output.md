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
# Warmup Iteration   1: 1.196 ops/ms
# Warmup Iteration   2: 2.728 ops/ms
# Warmup Iteration   3: 5.846 ops/ms
Iteration   1: 5.829 ops/ms
Iteration   2: 6.334 ops/ms
Iteration   3: 6.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.262 ±(99.9%) 7.343 ops/ms [Average]
  (min, avg, max) = (5.829, 6.262, 6.624), stdev = 0.403
  CI (99.9%): [≈ 0, 13.606] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.791 ops/ms
# Warmup Iteration   2: 5.843 ops/ms
# Warmup Iteration   3: 6.864 ops/ms
Iteration   1: 6.444 ops/ms
Iteration   2: 6.442 ops/ms
Iteration   3: 6.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.544 ±(99.9%) 3.181 ops/ms [Average]
  (min, avg, max) = (6.442, 6.544, 6.745), stdev = 0.174
  CI (99.9%): [3.362, 9.725] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.789 ops/ms
# Warmup Iteration   2: 5.343 ops/ms
# Warmup Iteration   3: 6.192 ops/ms
Iteration   1: 6.051 ops/ms
Iteration   2: 6.238 ops/ms
Iteration   3: 6.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.173 ±(99.9%) 1.920 ops/ms [Average]
  (min, avg, max) = (6.051, 6.173, 6.238), stdev = 0.105
  CI (99.9%): [4.253, 8.093] (assumes normal distribution)


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
# Warmup Iteration   1: 1.841 ops/ms
# Warmup Iteration   2: 4.312 ops/ms
# Warmup Iteration   3: 5.233 ops/ms
Iteration   1: 5.407 ops/ms
Iteration   2: 5.346 ops/ms
Iteration   3: 5.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.328 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (5.232, 5.328, 5.407), stdev = 0.089
  CI (99.9%): [3.707, 6.950] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 16.620 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.318 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.306 ±(99.9%) 0.018 ms/op
Iteration   1: 5.363 ±(99.9%) 0.009 ms/op
Iteration   2: 5.148 ±(99.9%) 0.025 ms/op
Iteration   3: 5.563 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.358 ±(99.9%) 3.788 ms/op [Average]
  (min, avg, max) = (5.148, 5.358, 5.563), stdev = 0.208
  CI (99.9%): [1.570, 9.146] (assumes normal distribution)


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
# Warmup Iteration   1: 16.846 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.800 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.245 ±(99.9%) 0.011 ms/op
Iteration   1: 4.946 ±(99.9%) 0.023 ms/op
Iteration   2: 4.951 ±(99.9%) 0.016 ms/op
Iteration   3: 5.083 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.993 ±(99.9%) 1.420 ms/op [Average]
  (min, avg, max) = (4.946, 4.993, 5.083), stdev = 0.078
  CI (99.9%): [3.573, 6.413] (assumes normal distribution)


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
# Warmup Iteration   1: 15.431 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.866 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.221 ±(99.9%) 0.009 ms/op
Iteration   1: 4.958 ±(99.9%) 0.013 ms/op
Iteration   2: 5.270 ±(99.9%) 0.010 ms/op
Iteration   3: 5.071 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.099 ±(99.9%) 2.882 ms/op [Average]
  (min, avg, max) = (4.958, 5.099, 5.270), stdev = 0.158
  CI (99.9%): [2.218, 7.981] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.070 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 7.446 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.928 ±(99.9%) 0.014 ms/op
Iteration   1: 6.100 ±(99.9%) 0.008 ms/op
Iteration   2: 6.051 ±(99.9%) 0.017 ms/op
Iteration   3: 5.751 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.967 ±(99.9%) 3.442 ms/op [Average]
  (min, avg, max) = (5.751, 5.967, 6.100), stdev = 0.189
  CI (99.9%): [2.526, 9.409] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.861 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 6.210 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.491 ±(99.9%) 0.021 ms/op
Iteration   1: 5.350 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   11.026 ms/op
                 createUser·p0.999:  23.003 ms/op
                 createUser·p0.9999: 33.293 ms/op
                 createUser·p1.00:   34.996 ms/op

Iteration   2: 5.404 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.496 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   8.970 ms/op
                 createUser·p0.999:  25.993 ms/op
                 createUser·p0.9999: 32.914 ms/op
                 createUser·p1.00:   34.472 ms/op

Iteration   3: 5.350 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.322 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.119 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  24.936 ms/op
                 createUser·p0.9999: 29.470 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178815
  mean =      5.368 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 78408 
    [ 5.000,  7.500) = 93040 
    [ 7.500, 10.000) = 5735 
    [10.000, 12.500) = 964 
    [12.500, 15.000) = 369 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =      9.795 ms/op
     p(99.9000) =     23.370 ms/op
     p(99.9900) =     32.739 ms/op
     p(99.9990) =     34.686 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.925 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 6.030 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.300 ±(99.9%) 0.019 ms/op
Iteration   1: 4.929 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.134 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   5.726 ms/op
                 existUser·p0.95:   6.513 ms/op
                 existUser·p0.99:   9.404 ms/op
                 existUser·p0.999:  22.446 ms/op
                 existUser·p0.9999: 25.904 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 5.177 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.177 ms/op
                 existUser·p0.95:   6.840 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  22.526 ms/op
                 existUser·p0.9999: 27.317 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 5.149 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   6.742 ms/op
                 existUser·p0.99:   9.188 ms/op
                 existUser·p0.999:  27.033 ms/op
                 existUser·p0.9999: 39.439 ms/op
                 existUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188674
  mean =      5.082 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 110927 
    [ 5.000, 10.000) = 76338 
    [10.000, 15.000) = 1073 
    [15.000, 20.000) = 116 
    [20.000, 25.000) = 94 
    [25.000, 30.000) = 94 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.935 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     22.489 ms/op
     p(99.9900) =     38.880 ms/op
     p(99.9990) =     40.247 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


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
# Warmup Iteration   1: 18.307 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 6.698 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.696 ±(99.9%) 0.021 ms/op
Iteration   1: 5.072 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.638 ms/op
                 getUser·p0.50:   4.841 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  24.403 ms/op
                 getUser·p0.9999: 28.062 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   2: 5.334 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.995 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.366 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  24.090 ms/op
                 getUser·p0.9999: 27.788 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   3: 5.264 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.956 ms/op
                 getUser·p0.50:   5.054 ms/op
                 getUser·p0.90:   6.332 ms/op
                 getUser·p0.95:   6.980 ms/op
                 getUser·p0.99:   8.864 ms/op
                 getUser·p0.999:  27.527 ms/op
                 getUser·p0.9999: 38.732 ms/op
                 getUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183772
  mean =      5.221 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 96699 
    [ 5.000,  7.500) = 80075 
    [ 7.500, 10.000) = 5529 
    [10.000, 12.500) = 930 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.956 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.349 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     24.296 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     39.288 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 19.505 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 7.481 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.177 ±(99.9%) 0.019 ms/op
Iteration   1: 6.408 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.060 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   8.225 ms/op
                 listUser·p0.95:   9.486 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  24.510 ms/op
                 listUser·p0.9999: 28.148 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   2: 5.892 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.203 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  24.010 ms/op
                 listUser·p0.9999: 27.268 ms/op
                 listUser·p1.00:   28.148 ms/op

Iteration   3: 6.199 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.102 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  21.189 ms/op
                 listUser·p0.9999: 24.800 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155817
  mean =      6.159 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 9594 
    [ 5.000,  7.500) = 131290 
    [ 7.500, 10.000) = 11065 
    [10.000, 12.500) = 2907 
    [12.500, 15.000) = 488 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      5.825 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.685 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     23.402 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     29.029 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.262 ± 7.343  ops/ms
ClientPb.existUser                       thrpt       3   6.544 ± 3.181  ops/ms
ClientPb.getUser                         thrpt       3   6.173 ± 1.920  ops/ms
ClientPb.listUser                        thrpt       3   5.328 ± 1.622  ops/ms
ClientPb.createUser                       avgt       3   5.358 ± 3.788   ms/op
ClientPb.existUser                        avgt       3   4.993 ± 1.420   ms/op
ClientPb.getUser                          avgt       3   5.099 ± 2.882   ms/op
ClientPb.listUser                         avgt       3   5.967 ± 3.442   ms/op
ClientPb.createUser                     sample  178815   5.368 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.310           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.112           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.537           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.795           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.370           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.739           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  188674   5.082 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.062           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.709           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.437           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.489           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.880           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.305           ms/op
ClientPb.getUser                        sample  183772   5.221 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.956           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.086           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.503           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.296           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.683           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.453           ms/op
ClientPb.listUser                       sample  155817   6.159 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.825           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.430           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.685           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.485           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.296           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.688           ms/op
