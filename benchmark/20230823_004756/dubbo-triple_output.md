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
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 5.594 ops/ms
# Warmup Iteration   3: 8.523 ops/ms
Iteration   1: 9.225 ops/ms
Iteration   2: 9.252 ops/ms
Iteration   3: 9.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.219 ±(99.9%) 0.667 ops/ms [Average]
  (min, avg, max) = (9.179, 9.219, 9.252), stdev = 0.037
  CI (99.9%): [8.551, 9.886] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.833 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 9.554 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 9.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.742 ±(99.9%) 3.507 ops/ms [Average]
  (min, avg, max) = (9.623, 9.742, 9.963), stdev = 0.192
  CI (99.9%): [6.235, 13.248] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.691 ops/ms
# Warmup Iteration   2: 7.944 ops/ms
# Warmup Iteration   3: 9.232 ops/ms
Iteration   1: 8.795 ops/ms
Iteration   2: 9.187 ops/ms
Iteration   3: 9.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.071 ±(99.9%) 4.383 ops/ms [Average]
  (min, avg, max) = (8.795, 9.071, 9.231), stdev = 0.240
  CI (99.9%): [4.688, 13.454] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.607 ops/ms
# Warmup Iteration   2: 7.145 ops/ms
# Warmup Iteration   3: 7.812 ops/ms
Iteration   1: 7.856 ops/ms
Iteration   2: 7.816 ops/ms
Iteration   3: 7.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.829 ±(99.9%) 0.422 ops/ms [Average]
  (min, avg, max) = (7.815, 7.829, 7.856), stdev = 0.023
  CI (99.9%): [7.407, 8.251] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.775 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.005 ms/op
Iteration   1: 3.553 ±(99.9%) 0.011 ms/op
Iteration   2: 3.562 ±(99.9%) 0.006 ms/op
Iteration   3: 3.452 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.522 ±(99.9%) 1.119 ms/op [Average]
  (min, avg, max) = (3.452, 3.522, 3.562), stdev = 0.061
  CI (99.9%): [2.403, 4.641] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.870 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.004 ms/op
Iteration   1: 3.314 ±(99.9%) 0.003 ms/op
Iteration   2: 3.453 ±(99.9%) 0.004 ms/op
Iteration   3: 3.370 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.379 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.314, 3.379, 3.453), stdev = 0.070
  CI (99.9%): [2.094, 4.664] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.987 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.005 ms/op
Iteration   1: 3.591 ±(99.9%) 0.004 ms/op
Iteration   2: 3.421 ±(99.9%) 0.005 ms/op
Iteration   3: 3.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.488 ±(99.9%) 1.645 ms/op [Average]
  (min, avg, max) = (3.421, 3.488, 3.591), stdev = 0.090
  CI (99.9%): [1.843, 5.134] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.249 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.005 ms/op
Iteration   1: 4.074 ±(99.9%) 0.005 ms/op
Iteration   2: 3.955 ±(99.9%) 0.008 ms/op
Iteration   3: 4.093 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.041 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (3.955, 4.041, 4.093), stdev = 0.075
  CI (99.9%): [2.676, 5.405] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.497 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.010 ms/op
Iteration   1: 3.499 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   7.400 ms/op
                 createUser·p0.999:  20.170 ms/op
                 createUser·p0.9999: 24.796 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   2: 3.484 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 28.601 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  16.436 ms/op
                 createUser·p0.9999: 29.358 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275860
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4974 
    [ 2.500,  5.000) = 263631 
    [ 5.000,  7.500) = 4990 
    [ 7.500, 10.000) = 1573 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     16.968 ms/op
     p(99.9900) =     28.634 ms/op
     p(99.9990) =     29.906 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 8.230 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.010 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  19.997 ms/op
                 existUser·p0.9999: 26.491 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   2: 3.499 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  14.211 ms/op
                 existUser·p0.9999: 27.094 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 3.338 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  23.331 ms/op
                 existUser·p0.9999: 31.719 ms/op
                 existUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282986
  mean =      3.392 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9674 
    [ 2.500,  5.000) = 266001 
    [ 5.000,  7.500) = 5956 
    [ 7.500, 10.000) = 850 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     30.202 ms/op
     p(99.9990) =     32.053 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 10.282 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.485 ±(99.9%) 0.012 ms/op
Iteration   1: 3.531 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  21.218 ms/op
                 getUser·p0.9999: 28.932 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 3.494 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  21.645 ms/op
                 getUser·p0.9999: 26.528 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.354 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.731 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  21.890 ms/op
                 getUser·p0.9999: 34.537 ms/op
                 getUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277372
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3556 
    [ 2.500,  5.000) = 263954 
    [ 5.000,  7.500) = 8029 
    [ 7.500, 10.000) = 1263 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     21.365 ms/op
     p(99.9900) =     32.737 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 9.985 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.397 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.013 ms/op
Iteration   1: 4.059 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.847 ms/op
                 listUser·p0.99:   8.021 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 23.531 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 4.037 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.539 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 17.894 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 4.097 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  14.107 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236220
  mean =      4.064 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 225322 
    [ 5.000,  7.500) = 7982 
    [ 7.500, 10.000) = 1793 
    [10.000, 12.500) = 547 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     15.791 ms/op
     p(99.9900) =     22.065 ms/op
     p(99.9990) =     23.915 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.219 ± 0.667  ops/ms
ClientPb.existUser                       thrpt       3   9.742 ± 3.507  ops/ms
ClientPb.getUser                         thrpt       3   9.071 ± 4.383  ops/ms
ClientPb.listUser                        thrpt       3   7.829 ± 0.422  ops/ms
ClientPb.createUser                       avgt       3   3.522 ± 1.119   ms/op
ClientPb.existUser                        avgt       3   3.379 ± 1.285   ms/op
ClientPb.getUser                          avgt       3   3.488 ± 1.645   ms/op
ClientPb.listUser                         avgt       3   4.041 ± 1.365   ms/op
ClientPb.createUser                     sample  275860   3.479 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.663           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.881           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.968           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.634           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.064           ms/op
ClientPb.existUser                      sample  282986   3.392 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.768           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.499           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.202           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.309           ms/op
ClientPb.getUser                        sample  277372   3.458 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.343           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.930           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.365           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.737           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  236220   4.064 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.791           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.065           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.052           ms/op
