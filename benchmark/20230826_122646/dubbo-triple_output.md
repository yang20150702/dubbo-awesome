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
# Warmup Iteration   1: 1.156 ops/ms
# Warmup Iteration   2: 2.766 ops/ms
# Warmup Iteration   3: 5.206 ops/ms
Iteration   1: 5.516 ops/ms
Iteration   2: 5.729 ops/ms
Iteration   3: 5.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.711 ±(99.9%) 3.394 ops/ms [Average]
  (min, avg, max) = (5.516, 5.711, 5.887), stdev = 0.186
  CI (99.9%): [2.317, 9.105] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.675 ops/ms
# Warmup Iteration   2: 4.841 ops/ms
# Warmup Iteration   3: 6.100 ops/ms
Iteration   1: 6.195 ops/ms
Iteration   2: 6.271 ops/ms
Iteration   3: 6.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.274 ±(99.9%) 1.463 ops/ms [Average]
  (min, avg, max) = (6.195, 6.274, 6.355), stdev = 0.080
  CI (99.9%): [4.810, 7.737] (assumes normal distribution)


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
# Warmup Iteration   1: 1.837 ops/ms
# Warmup Iteration   2: 4.979 ops/ms
# Warmup Iteration   3: 5.890 ops/ms
Iteration   1: 5.836 ops/ms
Iteration   2: 5.879 ops/ms
Iteration   3: 6.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.944 ±(99.9%) 2.766 ops/ms [Average]
  (min, avg, max) = (5.836, 5.944, 6.117), stdev = 0.152
  CI (99.9%): [3.178, 8.710] (assumes normal distribution)


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
# Warmup Iteration   1: 1.421 ops/ms
# Warmup Iteration   2: 4.212 ops/ms
# Warmup Iteration   3: 4.926 ops/ms
Iteration   1: 4.970 ops/ms
Iteration   2: 5.061 ops/ms
Iteration   3: 4.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.965 ±(99.9%) 1.800 ops/ms [Average]
  (min, avg, max) = (4.864, 4.965, 5.061), stdev = 0.099
  CI (99.9%): [3.165, 6.765] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.806 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 6.413 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.901 ±(99.9%) 0.008 ms/op
Iteration   1: 5.374 ±(99.9%) 0.007 ms/op
Iteration   2: 5.571 ±(99.9%) 0.005 ms/op
Iteration   3: 5.406 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.450 ±(99.9%) 1.927 ms/op [Average]
  (min, avg, max) = (5.374, 5.450, 5.571), stdev = 0.106
  CI (99.9%): [3.523, 7.377] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.682 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.522 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.345 ±(99.9%) 0.010 ms/op
Iteration   1: 5.228 ±(99.9%) 0.007 ms/op
Iteration   2: 5.306 ±(99.9%) 0.008 ms/op
Iteration   3: 5.169 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.234 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (5.169, 5.234, 5.306), stdev = 0.069
  CI (99.9%): [3.983, 6.485] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.625 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.286 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.519 ±(99.9%) 0.009 ms/op
Iteration   1: 5.226 ±(99.9%) 0.016 ms/op
Iteration   2: 5.759 ±(99.9%) 0.008 ms/op
Iteration   3: 5.469 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.484 ±(99.9%) 4.868 ms/op [Average]
  (min, avg, max) = (5.226, 5.484, 5.759), stdev = 0.267
  CI (99.9%): [0.616, 10.353] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.663 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.492 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.484 ±(99.9%) 0.009 ms/op
Iteration   1: 6.348 ±(99.9%) 0.012 ms/op
Iteration   2: 6.284 ±(99.9%) 0.022 ms/op
Iteration   3: 6.089 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.240 ±(99.9%) 2.456 ms/op [Average]
  (min, avg, max) = (6.089, 6.240, 6.348), stdev = 0.135
  CI (99.9%): [3.784, 8.696] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.588 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 7.062 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.132 ±(99.9%) 0.031 ms/op
Iteration   1: 5.487 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   8.266 ms/op
                 createUser·p0.99:   11.518 ms/op
                 createUser·p0.999:  15.483 ms/op
                 createUser·p0.9999: 26.515 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   2: 5.499 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.856 ms/op
                 createUser·p0.95:   7.856 ms/op
                 createUser·p0.99:   10.895 ms/op
                 createUser·p0.999:  33.223 ms/op
                 createUser·p0.9999: 39.480 ms/op
                 createUser·p1.00:   41.681 ms/op

Iteration   3: 5.599 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.963 ms/op
                 createUser·p0.95:   8.118 ms/op
                 createUser·p0.99:   11.387 ms/op
                 createUser·p0.999:  29.748 ms/op
                 createUser·p0.9999: 33.531 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173593
  mean =      5.528 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 68835 
    [ 5.000, 10.000) = 101654 
    [10.000, 15.000) = 2692 
    [15.000, 20.000) = 216 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 40 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 41 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      8.069 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     21.705 ms/op
     p(99.9900) =     38.404 ms/op
     p(99.9990) =     41.681 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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
# Warmup Iteration   1: 16.146 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 6.788 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.393 ±(99.9%) 0.021 ms/op
Iteration   1: 5.154 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.980 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.340 ms/op
                 existUser·p0.99:   10.174 ms/op
                 existUser·p0.999:  20.177 ms/op
                 existUser·p0.9999: 25.807 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   2: 5.195 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.544 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.726 ms/op
                 existUser·p0.95:   7.578 ms/op
                 existUser·p0.99:   10.748 ms/op
                 existUser·p0.999:  24.183 ms/op
                 existUser·p0.9999: 32.430 ms/op
                 existUser·p1.00:   32.637 ms/op

Iteration   3: 5.145 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.390 ms/op
                 existUser·p0.95:   7.365 ms/op
                 existUser·p0.99:   10.012 ms/op
                 existUser·p0.999:  16.299 ms/op
                 existUser·p0.9999: 28.958 ms/op
                 existUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185844
  mean =      5.165 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 107537 
    [ 5.000,  7.500) = 69421 
    [ 7.500, 10.000) = 6647 
    [10.000, 12.500) = 1484 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.980 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.438 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     30.621 ms/op
     p(99.9990) =     32.581 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.972 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.384 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.466 ±(99.9%) 0.021 ms/op
Iteration   1: 5.490 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.576 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.824 ms/op
                 getUser·p0.95:   8.118 ms/op
                 getUser·p0.99:   11.807 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 29.634 ms/op
                 getUser·p1.00:   31.425 ms/op

Iteration   2: 5.704 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.487 ms/op
                 getUser·p0.95:   8.929 ms/op
                 getUser·p0.99:   12.763 ms/op
                 getUser·p0.999:  26.211 ms/op
                 getUser·p0.9999: 34.013 ms/op
                 getUser·p1.00:   34.931 ms/op

Iteration   3: 5.639 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   7.242 ms/op
                 getUser·p0.95:   8.520 ms/op
                 getUser·p0.99:   12.452 ms/op
                 getUser·p0.999:  26.968 ms/op
                 getUser·p0.9999: 30.704 ms/op
                 getUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170986
  mean =      5.610 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 66647 
    [ 5.000,  7.500) = 89980 
    [ 7.500, 10.000) = 10130 
    [10.000, 12.500) = 2619 
    [12.500, 15.000) = 1054 
    [15.000, 17.500) = 250 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     12.290 ms/op
     p(99.9000) =     24.741 ms/op
     p(99.9900) =     31.841 ms/op
     p(99.9990) =     34.465 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 18.881 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.842 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 6.772 ±(99.9%) 0.033 ms/op
Iteration   1: 6.401 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.064 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  31.437 ms/op
                 listUser·p0.9999: 38.994 ms/op
                 listUser·p1.00:   39.453 ms/op

Iteration   2: 6.623 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   6.218 ms/op
                 listUser·p0.90:   8.094 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   14.320 ms/op
                 listUser·p0.999:  31.667 ms/op
                 listUser·p0.9999: 39.082 ms/op
                 listUser·p1.00:   43.057 ms/op

Iteration   3: 6.188 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   11.895 ms/op
                 listUser·p0.999:  26.649 ms/op
                 listUser·p0.9999: 31.236 ms/op
                 listUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149999
  mean =      6.399 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8918 
    [ 5.000, 10.000) = 136049 
    [10.000, 15.000) = 4189 
    [15.000, 20.000) = 484 
    [20.000, 25.000) = 94 
    [25.000, 30.000) = 106 
    [30.000, 35.000) = 106 
    [35.000, 40.000) = 52 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      5.997 ms/op
     p(90.0000) =      7.864 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     12.747 ms/op
     p(99.9000) =     30.147 ms/op
     p(99.9900) =     38.732 ms/op
     p(99.9990) =     41.255 ms/op
     p(99.9999) =     43.057 ms/op
    p(100.0000) =     43.057 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.711 ± 3.394  ops/ms
ClientPb.existUser                       thrpt       3   6.274 ± 1.463  ops/ms
ClientPb.getUser                         thrpt       3   5.944 ± 2.766  ops/ms
ClientPb.listUser                        thrpt       3   4.965 ± 1.800  ops/ms
ClientPb.createUser                       avgt       3   5.450 ± 1.927   ms/op
ClientPb.existUser                        avgt       3   5.234 ± 1.251   ms/op
ClientPb.getUser                          avgt       3   5.484 ± 4.868   ms/op
ClientPb.listUser                         avgt       3   6.240 ± 2.456   ms/op
ClientPb.createUser                     sample  173593   5.528 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.228           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.069           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.354           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.705           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.404           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.681           ms/op
ClientPb.existUser                      sample  185844   5.165 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.980           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.496           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.438           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.387           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.350           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.621           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.637           ms/op
ClientPb.getUser                        sample  170986   5.610 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.811           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.210           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.176           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.552           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.290           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.741           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.841           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.931           ms/op
ClientPb.listUser                       sample  149999   6.399 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.997           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.747           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.147           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.732           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.057           ms/op
