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
# Warmup Iteration   1: 1.943 ops/ms
# Warmup Iteration   2: 4.377 ops/ms
# Warmup Iteration   3: 8.268 ops/ms
Iteration   1: 8.808 ops/ms
Iteration   2: 8.964 ops/ms
Iteration   3: 9.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.978 ±(99.9%) 3.223 ops/ms [Average]
  (min, avg, max) = (8.808, 8.978, 9.161), stdev = 0.177
  CI (99.9%): [5.754, 12.201] (assumes normal distribution)


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
# Warmup Iteration   1: 2.509 ops/ms
# Warmup Iteration   2: 8.261 ops/ms
# Warmup Iteration   3: 9.183 ops/ms
Iteration   1: 9.432 ops/ms
Iteration   2: 9.362 ops/ms
Iteration   3: 9.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.487 ±(99.9%) 2.904 ops/ms [Average]
  (min, avg, max) = (9.362, 9.487, 9.666), stdev = 0.159
  CI (99.9%): [6.583, 12.390] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.771 ops/ms
# Warmup Iteration   2: 8.358 ops/ms
# Warmup Iteration   3: 9.104 ops/ms
Iteration   1: 9.179 ops/ms
Iteration   2: 8.927 ops/ms
Iteration   3: 9.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.078 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (8.927, 9.078, 9.179), stdev = 0.134
  CI (99.9%): [6.641, 11.516] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.571 ops/ms
# Warmup Iteration   2: 6.591 ops/ms
# Warmup Iteration   3: 7.565 ops/ms
Iteration   1: 7.602 ops/ms
Iteration   2: 7.692 ops/ms
Iteration   3: 7.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.628 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (7.590, 7.628, 7.692), stdev = 0.056
  CI (99.9%): [6.613, 8.643] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.187 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.006 ms/op
Iteration   1: 3.690 ±(99.9%) 0.005 ms/op
Iteration   2: 3.502 ±(99.9%) 0.004 ms/op
Iteration   3: 3.478 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.556 ±(99.9%) 2.119 ms/op [Average]
  (min, avg, max) = (3.478, 3.556, 3.690), stdev = 0.116
  CI (99.9%): [1.438, 5.675] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.370 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.004 ms/op
Iteration   1: 3.411 ±(99.9%) 0.004 ms/op
Iteration   2: 3.428 ±(99.9%) 0.006 ms/op
Iteration   3: 3.362 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.400 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.362, 3.400, 3.428), stdev = 0.035
  CI (99.9%): [2.771, 4.030] (assumes normal distribution)


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
# Warmup Iteration   1: 10.587 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.003 ms/op
Iteration   1: 3.548 ±(99.9%) 0.004 ms/op
Iteration   2: 3.578 ±(99.9%) 0.005 ms/op
Iteration   3: 3.510 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.545 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.510, 3.545, 3.578), stdev = 0.034
  CI (99.9%): [2.926, 4.164] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.614 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.005 ms/op
Iteration   1: 4.325 ±(99.9%) 0.005 ms/op
Iteration   2: 4.060 ±(99.9%) 0.009 ms/op
Iteration   3: 4.212 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.199 ±(99.9%) 2.425 ms/op [Average]
  (min, avg, max) = (4.060, 4.199, 4.325), stdev = 0.133
  CI (99.9%): [1.774, 6.623] (assumes normal distribution)


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
# Warmup Iteration   1: 12.707 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.016 ms/op
Iteration   1: 3.642 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.397 ms/op
                 createUser·p0.999:  18.252 ms/op
                 createUser·p0.9999: 26.268 ms/op
                 createUser·p1.00:   30.573 ms/op

Iteration   2: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.896 ms/op
                 createUser·p0.999:  18.205 ms/op
                 createUser·p0.9999: 26.367 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   3: 3.547 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   7.239 ms/op
                 createUser·p0.999:  21.135 ms/op
                 createUser·p0.9999: 24.144 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269743
  mean =      3.558 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3472 
    [ 2.500,  5.000) = 256631 
    [ 5.000,  7.500) = 7497 
    [ 7.500, 10.000) = 1252 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 9.333 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.009 ms/op
Iteration   1: 3.513 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  21.496 ms/op
                 existUser·p0.9999: 23.518 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   7.725 ms/op
                 existUser·p0.999:  14.622 ms/op
                 existUser·p0.9999: 24.423 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.401 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.392 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  22.338 ms/op
                 existUser·p0.9999: 54.971 ms/op
                 existUser·p1.00:   56.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278284
  mean =      3.447 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270949 
    [ 5.000, 10.000) = 6663 
    [10.000, 15.000) = 360 
    [15.000, 20.000) = 37 
    [20.000, 25.000) = 220 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     46.654 ms/op
     p(99.9990) =     56.048 ms/op
     p(99.9999) =     56.492 ms/op
    p(100.0000) =     56.492 ms/op


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
# Warmup Iteration   1: 9.579 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.012 ms/op
Iteration   1: 3.733 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  20.752 ms/op
                 getUser·p0.9999: 23.804 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.456 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.366 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  23.112 ms/op
                 getUser·p0.9999: 26.305 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 3.605 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  19.137 ms/op
                 getUser·p0.9999: 27.326 ms/op
                 getUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266964
  mean =      3.594 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2862 
    [ 2.500,  5.000) = 253832 
    [ 5.000,  7.500) = 6945 
    [ 7.500, 10.000) = 2514 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     26.388 ms/op
     p(99.9990) =     28.421 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 11.980 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.013 ms/op
Iteration   1: 4.211 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  20.618 ms/op
                 listUser·p0.9999: 26.412 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   2: 4.245 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  16.395 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 4.134 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.861 ms/op
                 listUser·p0.999:  14.150 ms/op
                 listUser·p0.9999: 16.499 ms/op
                 listUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228608
  mean =      4.196 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 117 
    [ 2.500,  5.000) = 217029 
    [ 5.000,  7.500) = 7725 
    [ 7.500, 10.000) = 2476 
    [10.000, 12.500) = 386 
    [12.500, 15.000) = 444 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     16.888 ms/op
     p(99.9900) =     24.843 ms/op
     p(99.9990) =     28.695 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.978 ± 3.223  ops/ms
ClientPb.existUser                       thrpt       3   9.487 ± 2.904  ops/ms
ClientPb.getUser                         thrpt       3   9.078 ± 2.438  ops/ms
ClientPb.listUser                        thrpt       3   7.628 ± 1.015  ops/ms
ClientPb.createUser                       avgt       3   3.556 ± 2.119   ms/op
ClientPb.existUser                        avgt       3   3.400 ± 0.630   ms/op
ClientPb.getUser                          avgt       3   3.545 ± 0.619   ms/op
ClientPb.listUser                         avgt       3   4.199 ± 2.425   ms/op
ClientPb.createUser                     sample  269743   3.558 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.182           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.678           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.051           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.573           ms/op
ClientPb.existUser                      sample  278284   3.447 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.392           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.037           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.727           ms/op
ClientPb.existUser:existUser·p0.9999    sample          46.654           ms/op
ClientPb.existUser:existUser·p1.00      sample          56.492           ms/op
ClientPb.getUser                        sample  266964   3.594 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.366           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.635           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.972           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.388           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.606           ms/op
ClientPb.listUser                       sample  228608   4.196 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.421           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.888           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.843           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.262           ms/op
