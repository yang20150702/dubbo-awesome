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
# Warmup Iteration   1: 2.073 ops/ms
# Warmup Iteration   2: 5.759 ops/ms
# Warmup Iteration   3: 8.646 ops/ms
Iteration   1: 9.615 ops/ms
Iteration   2: 9.188 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.368 ±(99.9%) 4.043 ops/ms [Average]
  (min, avg, max) = (9.188, 9.368, 9.615), stdev = 0.222
  CI (99.9%): [5.325, 13.410] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.867 ops/ms
# Warmup Iteration   2: 8.289 ops/ms
# Warmup Iteration   3: 9.246 ops/ms
Iteration   1: 9.708 ops/ms
Iteration   2: 9.738 ops/ms
Iteration   3: 9.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.685 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (9.607, 9.685, 9.738), stdev = 0.068
  CI (99.9%): [8.435, 10.934] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.695 ops/ms
# Warmup Iteration   2: 8.051 ops/ms
# Warmup Iteration   3: 9.420 ops/ms
Iteration   1: 9.326 ops/ms
Iteration   2: 9.402 ops/ms
Iteration   3: 9.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.334 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (9.274, 9.334, 9.402), stdev = 0.064
  CI (99.9%): [8.158, 10.511] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.630 ops/ms
# Warmup Iteration   2: 7.311 ops/ms
# Warmup Iteration   3: 8.013 ops/ms
Iteration   1: 7.853 ops/ms
Iteration   2: 8.366 ops/ms
Iteration   3: 7.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.018 ±(99.9%) 5.501 ops/ms [Average]
  (min, avg, max) = (7.835, 8.018, 8.366), stdev = 0.302
  CI (99.9%): [2.516, 13.519] (assumes normal distribution)


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
# Warmup Iteration   1: 9.082 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.008 ms/op
Iteration   1: 3.381 ±(99.9%) 0.009 ms/op
Iteration   2: 3.407 ±(99.9%) 0.008 ms/op
Iteration   3: 3.520 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.436 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (3.381, 3.436, 3.520), stdev = 0.074
  CI (99.9%): [2.084, 4.787] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.870 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.007 ms/op
Iteration   1: 3.233 ±(99.9%) 0.004 ms/op
Iteration   2: 3.275 ±(99.9%) 0.011 ms/op
Iteration   3: 3.251 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.233, 3.253, 3.275), stdev = 0.021
  CI (99.9%): [2.865, 3.641] (assumes normal distribution)


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
# Warmup Iteration   1: 8.589 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.005 ms/op
Iteration   1: 3.477 ±(99.9%) 0.007 ms/op
Iteration   2: 3.388 ±(99.9%) 0.006 ms/op
Iteration   3: 3.425 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.430 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (3.388, 3.430, 3.477), stdev = 0.045
  CI (99.9%): [2.611, 4.249] (assumes normal distribution)


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
# Warmup Iteration   1: 10.691 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.008 ms/op
Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
Iteration   2: 3.917 ±(99.9%) 0.013 ms/op
Iteration   3: 3.889 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.934 ±(99.9%) 1.006 ms/op [Average]
  (min, avg, max) = (3.889, 3.934, 3.996), stdev = 0.055
  CI (99.9%): [2.927, 4.940] (assumes normal distribution)


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
# Warmup Iteration   1: 10.554 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.014 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.346 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  18.364 ms/op
                 createUser·p0.9999: 22.409 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 3.387 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.110 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  20.623 ms/op
                 createUser·p0.9999: 23.582 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.439 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.834 ms/op
                 createUser·p0.999:  18.442 ms/op
                 createUser·p0.9999: 24.454 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278586
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8264 
    [ 2.500,  5.000) = 261344 
    [ 5.000,  7.500) = 7771 
    [ 7.500, 10.000) = 633 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     19.379 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.501 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 8.357 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
Iteration   1: 3.284 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  11.863 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.919 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  20.849 ms/op
                 existUser·p0.9999: 24.491 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.427 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.143 ms/op
                 existUser·p0.999:  11.272 ms/op
                 existUser·p0.9999: 30.988 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286703
  mean =      3.349 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18115 
    [ 2.500,  5.000) = 263138 
    [ 5.000,  7.500) = 4397 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     12.555 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     31.732 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 9.820 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.011 ms/op
Iteration   1: 3.369 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  20.155 ms/op
                 getUser·p0.9999: 22.922 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.410 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.417 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  21.434 ms/op
                 getUser·p0.9999: 29.184 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  19.853 ms/op
                 getUser·p0.9999: 26.149 ms/op
                 getUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279912
  mean =      3.428 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12967 
    [ 2.500,  5.000) = 260374 
    [ 5.000,  7.500) = 5426 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     29.583 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 10.784 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.013 ms/op
Iteration   1: 4.072 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  17.668 ms/op
                 listUser·p0.9999: 28.795 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 4.047 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   3: 3.985 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 22.114 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237698
  mean =      4.034 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 228263 
    [ 5.000,  7.500) = 6541 
    [ 7.500, 10.000) = 1842 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 360 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     27.129 ms/op
     p(99.9990) =     29.303 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.368 ± 4.043  ops/ms
ClientPb.existUser                       thrpt       3   9.685 ± 1.249  ops/ms
ClientPb.getUser                         thrpt       3   9.334 ± 1.177  ops/ms
ClientPb.listUser                        thrpt       3   8.018 ± 5.501  ops/ms
ClientPb.createUser                       avgt       3   3.436 ± 1.352   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 0.388   ms/op
ClientPb.getUser                          avgt       3   3.430 ± 0.819   ms/op
ClientPb.listUser                         avgt       3   3.934 ± 1.006   ms/op
ClientPb.createUser                     sample  278586   3.442 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.346           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.234           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.757           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.723           ms/op
ClientPb.existUser                      sample  286703   3.349 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.235           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.555           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.098           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  279912   3.428 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.659           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.152           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.591           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.819           ms/op
ClientPb.listUser                       sample  237698   4.034 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.056           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.647           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.129           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
