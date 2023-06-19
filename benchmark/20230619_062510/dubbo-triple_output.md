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
# Warmup Iteration   1: 2.021 ops/ms
# Warmup Iteration   2: 4.927 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 9.155 ops/ms
Iteration   2: 9.382 ops/ms
Iteration   3: 8.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.175 ±(99.9%) 3.616 ops/ms [Average]
  (min, avg, max) = (8.988, 9.175, 9.382), stdev = 0.198
  CI (99.9%): [5.559, 12.791] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.820 ops/ms
# Warmup Iteration   2: 8.812 ops/ms
# Warmup Iteration   3: 9.357 ops/ms
Iteration   1: 9.279 ops/ms
Iteration   2: 9.319 ops/ms
Iteration   3: 9.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.234 ±(99.9%) 2.095 ops/ms [Average]
  (min, avg, max) = (9.103, 9.234, 9.319), stdev = 0.115
  CI (99.9%): [7.139, 11.329] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.608 ops/ms
# Warmup Iteration   2: 8.215 ops/ms
# Warmup Iteration   3: 9.088 ops/ms
Iteration   1: 8.870 ops/ms
Iteration   2: 9.430 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.253 ±(99.9%) 6.058 ops/ms [Average]
  (min, avg, max) = (8.870, 9.253, 9.458), stdev = 0.332
  CI (99.9%): [3.194, 15.311] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.548 ops/ms
# Warmup Iteration   2: 6.858 ops/ms
# Warmup Iteration   3: 7.689 ops/ms
Iteration   1: 7.827 ops/ms
Iteration   2: 7.851 ops/ms
Iteration   3: 8.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.909 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (7.827, 7.909, 8.050), stdev = 0.122
  CI (99.9%): [5.676, 10.142] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.262 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.003 ms/op
Iteration   1: 3.418 ±(99.9%) 0.007 ms/op
Iteration   2: 3.498 ±(99.9%) 0.009 ms/op
Iteration   3: 3.330 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.415 ±(99.9%) 1.529 ms/op [Average]
  (min, avg, max) = (3.330, 3.415, 3.498), stdev = 0.084
  CI (99.9%): [1.886, 4.944] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.555 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.005 ms/op
Iteration   1: 3.257 ±(99.9%) 0.007 ms/op
Iteration   2: 3.380 ±(99.9%) 0.006 ms/op
Iteration   3: 3.369 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.335 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.257, 3.335, 3.380), stdev = 0.068
  CI (99.9%): [2.097, 4.574] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.385 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.006 ms/op
Iteration   1: 3.354 ±(99.9%) 0.010 ms/op
Iteration   2: 3.427 ±(99.9%) 0.005 ms/op
Iteration   3: 3.368 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.383 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (3.354, 3.383, 3.427), stdev = 0.039
  CI (99.9%): [2.678, 4.088] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.463 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.010 ms/op
Iteration   1: 4.076 ±(99.9%) 0.007 ms/op
Iteration   2: 3.967 ±(99.9%) 0.012 ms/op
Iteration   3: 4.092 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.045 ±(99.9%) 1.235 ms/op [Average]
  (min, avg, max) = (3.967, 4.045, 4.092), stdev = 0.068
  CI (99.9%): [2.809, 5.280] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.586 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.015 ms/op
Iteration   1: 3.463 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.878 ms/op
                 createUser·p0.999:  21.579 ms/op
                 createUser·p0.9999: 30.829 ms/op
                 createUser·p1.00:   31.523 ms/op

Iteration   2: 3.457 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  23.429 ms/op
                 createUser·p0.9999: 39.715 ms/op
                 createUser·p1.00:   40.370 ms/op

Iteration   3: 3.362 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  21.250 ms/op
                 createUser·p0.9999: 26.476 ms/op
                 createUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280004
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 273244 
    [ 5.000, 10.000) = 6274 
    [10.000, 15.000) = 154 
    [15.000, 20.000) = 40 
    [20.000, 25.000) = 177 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     21.496 ms/op
     p(99.9900) =     38.535 ms/op
     p(99.9990) =     40.305 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.316 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.008 ms/op
Iteration   1: 3.538 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  22.184 ms/op
                 existUser·p0.9999: 25.817 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   2: 3.388 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.299 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  23.711 ms/op
                 existUser·p0.9999: 29.102 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 3.325 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.955 ms/op
                 existUser·p0.999:  12.468 ms/op
                 existUser·p0.9999: 29.784 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280986
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12578 
    [ 2.500,  5.000) = 259968 
    [ 5.000,  7.500) = 7128 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     29.124 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.875 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.011 ms/op
Iteration   1: 3.550 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  22.050 ms/op
                 getUser·p0.9999: 25.493 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 3.551 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  25.428 ms/op
                 getUser·p0.9999: 33.227 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   3: 3.462 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  11.405 ms/op
                 getUser·p0.9999: 29.680 ms/op
                 getUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272436
  mean =      3.520 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6074 
    [ 2.500,  5.000) = 255717 
    [ 5.000,  7.500) = 9030 
    [ 7.500, 10.000) = 1140 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     12.194 ms/op
     p(99.9900) =     31.941 ms/op
     p(99.9990) =     33.704 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.503 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.186 ±(99.9%) 0.014 ms/op
Iteration   1: 4.048 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  22.610 ms/op
                 listUser·p0.9999: 24.513 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   2: 4.048 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.565 ms/op
                 listUser·p0.999:  16.006 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 4.017 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.075 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 16.648 ms/op
                 listUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237751
  mean =      4.038 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 230453 
    [ 5.000,  7.500) = 4947 
    [ 7.500, 10.000) = 1457 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     23.968 ms/op
     p(99.9990) =     26.546 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.175 ± 3.616  ops/ms
ClientPb.existUser                       thrpt       3   9.234 ± 2.095  ops/ms
ClientPb.getUser                         thrpt       3   9.253 ± 6.058  ops/ms
ClientPb.listUser                        thrpt       3   7.909 ± 2.233  ops/ms
ClientPb.createUser                       avgt       3   3.415 ± 1.529   ms/op
ClientPb.existUser                        avgt       3   3.335 ± 1.239   ms/op
ClientPb.getUser                          avgt       3   3.383 ± 0.705   ms/op
ClientPb.listUser                         avgt       3   4.045 ± 1.235   ms/op
ClientPb.createUser                     sample  280004   3.427 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.272           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.496           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.535           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.370           ms/op
ClientPb.existUser                      sample  280986   3.414 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.247           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.796           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.124           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.293           ms/op
ClientPb.getUser                        sample  272436   3.520 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.174           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.194           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.941           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.013           ms/op
ClientPb.listUser                       sample  237751   4.038 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.968           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.706           ms/op
