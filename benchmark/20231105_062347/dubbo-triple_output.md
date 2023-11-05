# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.314 ops/ms
# Warmup Iteration   2: 5.078 ops/ms
# Warmup Iteration   3: 8.923 ops/ms
Iteration   1: 9.321 ops/ms
Iteration   2: 9.180 ops/ms
Iteration   3: 9.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.280 ±(99.9%) 1.577 ops/ms [Average]
  (min, avg, max) = (9.180, 9.280, 9.337), stdev = 0.086
  CI (99.9%): [7.702, 10.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.815 ops/ms
# Warmup Iteration   2: 8.708 ops/ms
# Warmup Iteration   3: 9.489 ops/ms
Iteration   1: 9.970 ops/ms
Iteration   2: 9.612 ops/ms
Iteration   3: 9.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.752 ±(99.9%) 3.488 ops/ms [Average]
  (min, avg, max) = (9.612, 9.752, 9.970), stdev = 0.191
  CI (99.9%): [6.264, 13.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.169 ops/ms
# Warmup Iteration   2: 8.664 ops/ms
# Warmup Iteration   3: 9.199 ops/ms
Iteration   1: 9.410 ops/ms
Iteration   2: 9.480 ops/ms
Iteration   3: 9.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.375 ±(99.9%) 2.308 ops/ms [Average]
  (min, avg, max) = (9.234, 9.375, 9.480), stdev = 0.127
  CI (99.9%): [7.066, 11.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.751 ops/ms
# Warmup Iteration   2: 7.362 ops/ms
# Warmup Iteration   3: 7.616 ops/ms
Iteration   1: 7.736 ops/ms
Iteration   2: 7.626 ops/ms
Iteration   3: 7.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.664 ±(99.9%) 1.136 ops/ms [Average]
  (min, avg, max) = (7.626, 7.664, 7.736), stdev = 0.062
  CI (99.9%): [6.528, 8.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.705 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.003 ms/op
Iteration   1: 3.544 ±(99.9%) 0.005 ms/op
Iteration   2: 3.433 ±(99.9%) 0.006 ms/op
Iteration   3: 3.536 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.504 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.433, 3.504, 3.544), stdev = 0.062
  CI (99.9%): [2.369, 4.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.930 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.007 ms/op
Iteration   1: 3.302 ±(99.9%) 0.003 ms/op
Iteration   2: 3.327 ±(99.9%) 0.004 ms/op
Iteration   3: 3.320 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.316 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (3.302, 3.316, 3.327), stdev = 0.013
  CI (99.9%): [3.080, 3.553] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.084 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.002 ms/op
Iteration   1: 3.488 ±(99.9%) 0.002 ms/op
Iteration   2: 3.402 ±(99.9%) 0.005 ms/op
Iteration   3: 3.447 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.446 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.402, 3.446, 3.488), stdev = 0.043
  CI (99.9%): [2.659, 4.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.318 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.005 ms/op
Iteration   1: 4.096 ±(99.9%) 0.009 ms/op
Iteration   2: 4.060 ±(99.9%) 0.005 ms/op
Iteration   3: 4.081 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.079 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (4.060, 4.079, 4.096), stdev = 0.018
  CI (99.9%): [3.752, 4.406] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.811 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.011 ms/op
Iteration   1: 3.439 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.924 ms/op
                 createUser·p0.999:  18.970 ms/op
                 createUser·p0.9999: 22.328 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 3.463 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.816 ms/op
                 createUser·p0.999:  23.152 ms/op
                 createUser·p0.9999: 25.846 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.417 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  16.275 ms/op
                 createUser·p0.9999: 24.105 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279048
  mean =      3.440 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6128 
    [ 2.500,  5.000) = 266696 
    [ 5.000,  7.500) = 4996 
    [ 7.500, 10.000) = 541 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.263 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     26.156 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.866 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.007 ms/op
Iteration   1: 3.362 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  19.124 ms/op
                 existUser·p0.9999: 24.100 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.398 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  20.726 ms/op
                 existUser·p0.9999: 24.248 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 26.836 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282789
  mean =      3.393 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10936 
    [ 2.500,  5.000) = 266149 
    [ 5.000,  7.500) = 4579 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     14.733 ms/op
     p(99.9900) =     24.731 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.320 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.011 ms/op
Iteration   1: 3.450 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 23.084 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   2: 3.473 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.117 ms/op
                 getUser·p0.999:  20.901 ms/op
                 getUser·p0.9999: 23.888 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   3: 3.475 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  18.087 ms/op
                 getUser·p0.9999: 25.827 ms/op
                 getUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276883
  mean =      3.466 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5161 
    [ 2.500,  5.000) = 265210 
    [ 5.000,  7.500) = 5553 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     14.551 ms/op
     p(99.9900) =     24.619 ms/op
     p(99.9990) =     26.479 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.489 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.013 ms/op
Iteration   1: 4.242 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 27.409 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 4.034 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 16.205 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 4.147 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.063 ms/op
                 listUser·p0.999:  13.759 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231677
  mean =      4.139 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 222280 
    [ 5.000,  7.500) = 7836 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.957 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     24.964 ms/op
     p(99.9990) =     28.099 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.280 ± 1.577  ops/ms
ClientPb.existUser                       thrpt       3   9.752 ± 3.488  ops/ms
ClientPb.getUser                         thrpt       3   9.375 ± 2.308  ops/ms
ClientPb.listUser                        thrpt       3   7.664 ± 1.136  ops/ms
ClientPb.createUser                       avgt       3   3.504 ± 1.135   ms/op
ClientPb.existUser                        avgt       3   3.316 ± 0.237   ms/op
ClientPb.getUser                          avgt       3   3.446 ± 0.787   ms/op
ClientPb.listUser                         avgt       3   4.079 ± 0.327   ms/op
ClientPb.createUser                     sample  279048   3.440 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.973           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.263           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.974           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.264           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182           ms/op
ClientPb.existUser                      sample  282789   3.393 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.368           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.733           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.731           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.066           ms/op
ClientPb.getUser                        sample  276883   3.466 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.251           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.551           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.619           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.558           ms/op
ClientPb.listUser                       sample  231677   4.139 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.217           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.957           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.007           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.964           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.377           ms/op
