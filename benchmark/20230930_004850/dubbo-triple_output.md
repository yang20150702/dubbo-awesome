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
# Warmup Iteration   1: 2.243 ops/ms
# Warmup Iteration   2: 6.047 ops/ms
# Warmup Iteration   3: 8.682 ops/ms
Iteration   1: 9.215 ops/ms
Iteration   2: 9.314 ops/ms
Iteration   3: 9.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.320 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (9.215, 9.320, 9.431), stdev = 0.108
  CI (99.9%): [7.347, 11.292] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.816 ops/ms
# Warmup Iteration   2: 8.441 ops/ms
# Warmup Iteration   3: 9.525 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.724 ops/ms
Iteration   3: 9.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.503 ±(99.9%) 3.948 ops/ms [Average]
  (min, avg, max) = (9.291, 9.503, 9.724), stdev = 0.216
  CI (99.9%): [5.555, 13.451] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.157 ops/ms
# Warmup Iteration   2: 8.680 ops/ms
# Warmup Iteration   3: 8.640 ops/ms
Iteration   1: 9.131 ops/ms
Iteration   2: 9.220 ops/ms
Iteration   3: 9.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.164 ±(99.9%) 0.897 ops/ms [Average]
  (min, avg, max) = (9.131, 9.164, 9.220), stdev = 0.049
  CI (99.9%): [8.267, 10.061] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.794 ops/ms
# Warmup Iteration   2: 7.021 ops/ms
# Warmup Iteration   3: 7.885 ops/ms
Iteration   1: 7.610 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.753 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (7.610, 7.753, 7.869), stdev = 0.132
  CI (99.9%): [5.352, 10.154] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.663 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.007 ms/op
Iteration   1: 3.505 ±(99.9%) 0.005 ms/op
Iteration   2: 3.481 ±(99.9%) 0.006 ms/op
Iteration   3: 3.561 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.515 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (3.481, 3.515, 3.561), stdev = 0.041
  CI (99.9%): [2.764, 4.267] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.572 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.006 ms/op
Iteration   1: 3.363 ±(99.9%) 0.004 ms/op
Iteration   2: 3.442 ±(99.9%) 0.004 ms/op
Iteration   3: 3.351 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.385 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.351, 3.385, 3.442), stdev = 0.049
  CI (99.9%): [2.488, 4.282] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.021 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.003 ms/op
Iteration   1: 3.544 ±(99.9%) 0.004 ms/op
Iteration   2: 3.413 ±(99.9%) 0.004 ms/op
Iteration   3: 3.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.486 ±(99.9%) 1.217 ms/op [Average]
  (min, avg, max) = (3.413, 3.486, 3.544), stdev = 0.067
  CI (99.9%): [2.269, 4.703] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.658 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.006 ms/op
Iteration   1: 4.190 ±(99.9%) 0.006 ms/op
Iteration   2: 4.129 ±(99.9%) 0.005 ms/op
Iteration   3: 4.079 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.132 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (4.079, 4.132, 4.190), stdev = 0.055
  CI (99.9%): [3.120, 5.145] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.710 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.009 ms/op
Iteration   1: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  20.730 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.486 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 25.863 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  21.754 ms/op
                 createUser·p0.9999: 28.539 ms/op
                 createUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277721
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5342 
    [ 2.500,  5.000) = 267167 
    [ 5.000,  7.500) = 4207 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 164 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     21.168 ms/op
     p(99.9900) =     26.432 ms/op
     p(99.9990) =     29.400 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.456 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.008 ms/op
Iteration   1: 3.407 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  12.143 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.374 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  18.102 ms/op
                 existUser·p0.9999: 20.366 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.973 ms/op
                 existUser·p0.999:  18.777 ms/op
                 existUser·p0.9999: 23.790 ms/op
                 existUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283146
  mean =      3.389 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7543 
    [ 2.500,  5.000) = 270080 
    [ 5.000,  7.500) = 4473 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     22.960 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.734 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.010 ms/op
Iteration   1: 3.567 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  20.578 ms/op
                 getUser·p0.9999: 23.595 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  21.786 ms/op
                 getUser·p0.9999: 25.381 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.482 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  22.184 ms/op
                 getUser·p0.9999: 26.899 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273640
  mean =      3.507 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3843 
    [ 2.500,  5.000) = 261748 
    [ 5.000,  7.500) = 6624 
    [ 7.500, 10.000) = 641 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     20.819 ms/op
     p(99.9900) =     26.137 ms/op
     p(99.9990) =     27.599 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.281 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.013 ms/op
Iteration   1: 4.269 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 26.871 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 4.134 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.432 ms/op
                 listUser·p0.999:  15.265 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 4.182 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.869 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228638
  mean =      4.194 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 218892 
    [ 5.000,  7.500) = 7682 
    [ 7.500, 10.000) = 1089 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 231 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     25.230 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.320 ± 1.973  ops/ms
ClientPb.existUser                       thrpt       3   9.503 ± 3.948  ops/ms
ClientPb.getUser                         thrpt       3   9.164 ± 0.897  ops/ms
ClientPb.listUser                        thrpt       3   7.753 ± 2.401  ops/ms
ClientPb.createUser                       avgt       3   3.515 ± 0.751   ms/op
ClientPb.existUser                        avgt       3   3.385 ± 0.897   ms/op
ClientPb.getUser                          avgt       3   3.486 ± 1.217   ms/op
ClientPb.listUser                         avgt       3   4.132 ± 1.012   ms/op
ClientPb.createUser                     sample  277721   3.458 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.168           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.432           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  283146   3.389 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.094           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.647           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.960           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.904           ms/op
ClientPb.getUser                        sample  273640   3.507 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.935           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.819           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.137           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.820           ms/op
ClientPb.listUser                       sample  228638   4.194 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.155           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.230           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.296           ms/op
