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
# Warmup Iteration   1: 2.363 ops/ms
# Warmup Iteration   2: 5.461 ops/ms
# Warmup Iteration   3: 8.767 ops/ms
Iteration   1: 9.383 ops/ms
Iteration   2: 9.358 ops/ms
Iteration   3: 9.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.349 ±(99.9%) 0.705 ops/ms [Average]
  (min, avg, max) = (9.307, 9.349, 9.383), stdev = 0.039
  CI (99.9%): [8.644, 10.054] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 8.570 ops/ms
# Warmup Iteration   3: 9.341 ops/ms
Iteration   1: 9.857 ops/ms
Iteration   2: 9.983 ops/ms
Iteration   3: 9.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.893 ±(99.9%) 1.432 ops/ms [Average]
  (min, avg, max) = (9.838, 9.893, 9.983), stdev = 0.079
  CI (99.9%): [8.460, 11.325] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.132 ops/ms
# Warmup Iteration   2: 8.355 ops/ms
# Warmup Iteration   3: 9.444 ops/ms
Iteration   1: 9.405 ops/ms
Iteration   2: 9.648 ops/ms
Iteration   3: 9.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.458 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (9.321, 9.458, 9.648), stdev = 0.170
  CI (99.9%): [6.356, 12.560] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.784 ops/ms
# Warmup Iteration   2: 6.810 ops/ms
# Warmup Iteration   3: 7.934 ops/ms
Iteration   1: 8.018 ops/ms
Iteration   2: 8.295 ops/ms
Iteration   3: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.158 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (8.018, 8.158, 8.295), stdev = 0.138
  CI (99.9%): [5.633, 10.683] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.518 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.006 ms/op
Iteration   1: 3.375 ±(99.9%) 0.008 ms/op
Iteration   2: 3.427 ±(99.9%) 0.005 ms/op
Iteration   3: 3.329 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.377 ±(99.9%) 0.892 ms/op [Average]
  (min, avg, max) = (3.329, 3.377, 3.427), stdev = 0.049
  CI (99.9%): [2.484, 4.269] (assumes normal distribution)


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
# Warmup Iteration   1: 8.811 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.717 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.002 ms/op
Iteration   1: 3.257 ±(99.9%) 0.011 ms/op
Iteration   2: 3.308 ±(99.9%) 0.007 ms/op
Iteration   3: 3.245 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.270 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.245, 3.270, 3.308), stdev = 0.033
  CI (99.9%): [2.668, 3.872] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.847 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.004 ms/op
Iteration   1: 3.273 ±(99.9%) 0.013 ms/op
Iteration   2: 3.569 ±(99.9%) 0.005 ms/op
Iteration   3: 3.341 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.394 ±(99.9%) 2.824 ms/op [Average]
  (min, avg, max) = (3.273, 3.394, 3.569), stdev = 0.155
  CI (99.9%): [0.571, 6.218] (assumes normal distribution)


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
# Warmup Iteration   1: 9.943 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.973 ±(99.9%) 0.014 ms/op
Iteration   2: 3.963 ±(99.9%) 0.013 ms/op
Iteration   3: 4.020 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.986 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.963, 3.986, 4.020), stdev = 0.030
  CI (99.9%): [3.429, 4.542] (assumes normal distribution)


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
# Warmup Iteration   1: 8.524 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.008 ms/op
Iteration   1: 3.363 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  19.813 ms/op
                 createUser·p0.9999: 23.855 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   2: 3.376 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  19.800 ms/op
                 createUser·p0.9999: 22.365 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 3.400 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  17.338 ms/op
                 createUser·p0.9999: 24.223 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283776
  mean =      3.380 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18128 
    [ 2.500,  5.000) = 260751 
    [ 5.000,  7.500) = 3973 
    [ 7.500, 10.000) = 523 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 165 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     17.480 ms/op
     p(99.9900) =     23.679 ms/op
     p(99.9990) =     24.907 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.334 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.009 ms/op
Iteration   1: 3.419 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  21.118 ms/op
                 existUser·p0.9999: 23.242 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.585 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 25.346 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 3.281 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  13.124 ms/op
                 existUser·p0.9999: 26.509 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288524
  mean =      3.324 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5920 
    [ 2.500,  5.000) = 276373 
    [ 5.000,  7.500) = 5491 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     16.751 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     26.746 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 10.827 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.010 ms/op
Iteration   1: 3.333 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  18.713 ms/op
                 getUser·p0.9999: 22.033 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  19.953 ms/op
                 getUser·p0.9999: 23.455 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  18.229 ms/op
                 getUser·p0.9999: 23.443 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287996
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7250 
    [ 2.500,  5.000) = 275264 
    [ 5.000,  7.500) = 4507 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 180 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     23.272 ms/op
     p(99.9990) =     24.522 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 10.385 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.014 ms/op
Iteration   1: 4.136 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.000 ms/op
                 listUser·p0.999:  21.579 ms/op
                 listUser·p0.9999: 27.432 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 3.998 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 16.351 ms/op
                 listUser·p1.00:   16.646 ms/op

Iteration   3: 4.018 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 24.025 ms/op
                 listUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237040
  mean =      4.050 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 228107 
    [ 5.000,  7.500) = 6781 
    [ 7.500, 10.000) = 1350 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.908 ms/op
     p(99.9900) =     26.257 ms/op
     p(99.9990) =     28.365 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.349 ± 0.705  ops/ms
ClientPb.existUser                       thrpt       3   9.893 ± 1.432  ops/ms
ClientPb.getUser                         thrpt       3   9.458 ± 3.102  ops/ms
ClientPb.listUser                        thrpt       3   8.158 ± 2.525  ops/ms
ClientPb.createUser                       avgt       3   3.377 ± 0.892   ms/op
ClientPb.existUser                        avgt       3   3.270 ± 0.602   ms/op
ClientPb.getUser                          avgt       3   3.394 ± 2.824   ms/op
ClientPb.listUser                         avgt       3   3.986 ± 0.556   ms/op
ClientPb.createUser                     sample  283776   3.380 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.186           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.480           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.679           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.559           ms/op
ClientPb.existUser                      sample  288524   3.324 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.192           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.751           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.854           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  287996   3.332 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.217           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.759           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.272           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.609           ms/op
ClientPb.listUser                       sample  237040   4.050 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.460           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.257           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
