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
# Warmup Iteration   1: 2.054 ops/ms
# Warmup Iteration   2: 5.402 ops/ms
# Warmup Iteration   3: 8.732 ops/ms
Iteration   1: 9.127 ops/ms
Iteration   2: 9.029 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.173 ±(99.9%) 3.144 ops/ms [Average]
  (min, avg, max) = (9.029, 9.173, 9.364), stdev = 0.172
  CI (99.9%): [6.029, 12.317] (assumes normal distribution)


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
# Warmup Iteration   1: 3.483 ops/ms
# Warmup Iteration   2: 8.709 ops/ms
# Warmup Iteration   3: 9.475 ops/ms
Iteration   1: 9.653 ops/ms
Iteration   2: 9.777 ops/ms
Iteration   3: 9.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.753 ±(99.9%) 1.649 ops/ms [Average]
  (min, avg, max) = (9.653, 9.753, 9.829), stdev = 0.090
  CI (99.9%): [8.104, 11.401] (assumes normal distribution)


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
# Warmup Iteration   1: 3.042 ops/ms
# Warmup Iteration   2: 8.424 ops/ms
# Warmup Iteration   3: 9.201 ops/ms
Iteration   1: 9.526 ops/ms
Iteration   2: 9.072 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.345 ±(99.9%) 4.383 ops/ms [Average]
  (min, avg, max) = (9.072, 9.345, 9.526), stdev = 0.240
  CI (99.9%): [4.962, 13.728] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.930 ops/ms
# Warmup Iteration   2: 7.126 ops/ms
# Warmup Iteration   3: 7.963 ops/ms
Iteration   1: 8.014 ops/ms
Iteration   2: 7.793 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.946 ±(99.9%) 2.429 ops/ms [Average]
  (min, avg, max) = (7.793, 7.946, 8.033), stdev = 0.133
  CI (99.9%): [5.517, 10.376] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.196 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.006 ms/op
Iteration   1: 3.452 ±(99.9%) 0.006 ms/op
Iteration   2: 3.443 ±(99.9%) 0.007 ms/op
Iteration   3: 3.371 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.422 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.371, 3.422, 3.452), stdev = 0.045
  CI (99.9%): [2.607, 4.237] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.004 ms/op
Iteration   1: 3.266 ±(99.9%) 0.004 ms/op
Iteration   2: 3.229 ±(99.9%) 0.006 ms/op
Iteration   3: 3.289 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.261 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (3.229, 3.261, 3.289), stdev = 0.030
  CI (99.9%): [2.713, 3.809] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.205 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.006 ms/op
Iteration   1: 3.498 ±(99.9%) 0.002 ms/op
Iteration   2: 3.489 ±(99.9%) 0.003 ms/op
Iteration   3: 3.441 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.476 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.441, 3.476, 3.498), stdev = 0.031
  CI (99.9%): [2.919, 4.033] (assumes normal distribution)


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
# Warmup Iteration   1: 9.430 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.007 ms/op
Iteration   1: 4.096 ±(99.9%) 0.007 ms/op
Iteration   2: 3.947 ±(99.9%) 0.008 ms/op
Iteration   3: 3.936 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.993 ±(99.9%) 1.630 ms/op [Average]
  (min, avg, max) = (3.936, 3.993, 4.096), stdev = 0.089
  CI (99.9%): [2.363, 5.624] (assumes normal distribution)


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
# Warmup Iteration   1: 8.356 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
Iteration   1: 3.524 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  20.619 ms/op
                 createUser·p0.9999: 24.936 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   2: 3.456 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  21.345 ms/op
                 createUser·p0.9999: 24.895 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  17.499 ms/op
                 createUser·p0.9999: 26.044 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275338
  mean =      3.485 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5877 
    [ 2.500,  5.000) = 260509 
    [ 5.000,  7.500) = 7278 
    [ 7.500, 10.000) = 1035 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     18.110 ms/op
     p(99.9900) =     25.116 ms/op
     p(99.9990) =     26.581 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.545 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.009 ms/op
Iteration   1: 3.280 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  11.663 ms/op
                 existUser·p0.9999: 21.840 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  11.072 ms/op
                 existUser·p0.9999: 24.062 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 3.432 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.660 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  22.601 ms/op
                 existUser·p0.9999: 28.705 ms/op
                 existUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284120
  mean =      3.375 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5222 
    [ 2.500,  5.000) = 270951 
    [ 5.000,  7.500) = 6381 
    [ 7.500, 10.000) = 1030 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     30.987 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 9.306 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.011 ms/op
Iteration   1: 3.485 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  18.383 ms/op
                 getUser·p0.9999: 33.288 ms/op
                 getUser·p1.00:   33.882 ms/op

Iteration   2: 3.497 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  9.781 ms/op
                 getUser·p0.9999: 31.354 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   3: 3.485 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  22.282 ms/op
                 getUser·p0.9999: 26.471 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275252
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4196 
    [ 2.500,  5.000) = 259627 
    [ 5.000,  7.500) = 9755 
    [ 7.500, 10.000) = 1264 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     30.947 ms/op
     p(99.9990) =     33.767 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 10.005 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.015 ms/op
Iteration   1: 4.048 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  18.611 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   2: 4.015 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 3.947 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  15.434 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239865
  mean =      4.003 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 230712 
    [ 5.000,  7.500) = 6333 
    [ 7.500, 10.000) = 1777 
    [10.000, 12.500) = 531 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.667 ms/op
     p(99.0000) =      7.761 ms/op
     p(99.9000) =     15.586 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.361 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.173 ± 3.144  ops/ms
ClientPb.existUser                       thrpt       3   9.753 ± 1.649  ops/ms
ClientPb.getUser                         thrpt       3   9.345 ± 4.383  ops/ms
ClientPb.listUser                        thrpt       3   7.946 ± 2.429  ops/ms
ClientPb.createUser                       avgt       3   3.422 ± 0.815   ms/op
ClientPb.existUser                        avgt       3   3.261 ± 0.548   ms/op
ClientPb.getUser                          avgt       3   3.476 ± 0.557   ms/op
ClientPb.listUser                         avgt       3   3.993 ± 1.630   ms/op
ClientPb.createUser                     sample  275338   3.485 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.611           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.116           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.001           ms/op
ClientPb.existUser                      sample  284120   3.375 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.990           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.645           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.287           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.722           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.162           ms/op
ClientPb.getUser                        sample  275252   3.489 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.266           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.074           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.947           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  239865   4.003 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.559           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.667           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.761           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.586           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.233           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.674           ms/op
