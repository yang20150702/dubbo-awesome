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
# Warmup Iteration   1: 2.221 ops/ms
# Warmup Iteration   2: 5.802 ops/ms
# Warmup Iteration   3: 8.398 ops/ms
Iteration   1: 9.273 ops/ms
Iteration   2: 9.292 ops/ms
Iteration   3: 9.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.263 ±(99.9%) 0.644 ops/ms [Average]
  (min, avg, max) = (9.224, 9.263, 9.292), stdev = 0.035
  CI (99.9%): [8.619, 9.907] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.818 ops/ms
# Warmup Iteration   2: 8.271 ops/ms
# Warmup Iteration   3: 9.349 ops/ms
Iteration   1: 9.698 ops/ms
Iteration   2: 9.674 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.666 ±(99.9%) 0.664 ops/ms [Average]
  (min, avg, max) = (9.626, 9.666, 9.698), stdev = 0.036
  CI (99.9%): [9.002, 10.330] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.193 ops/ms
# Warmup Iteration   2: 8.566 ops/ms
# Warmup Iteration   3: 8.812 ops/ms
Iteration   1: 9.223 ops/ms
Iteration   2: 9.438 ops/ms
Iteration   3: 9.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.370 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (9.223, 9.370, 9.450), stdev = 0.128
  CI (99.9%): [7.035, 11.706] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.598 ops/ms
# Warmup Iteration   2: 7.150 ops/ms
# Warmup Iteration   3: 8.024 ops/ms
Iteration   1: 8.178 ops/ms
Iteration   2: 8.032 ops/ms
Iteration   3: 8.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.112 ±(99.9%) 1.349 ops/ms [Average]
  (min, avg, max) = (8.032, 8.112, 8.178), stdev = 0.074
  CI (99.9%): [6.762, 9.461] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.172 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.002 ms/op
Iteration   1: 3.362 ±(99.9%) 0.008 ms/op
Iteration   2: 3.418 ±(99.9%) 0.008 ms/op
Iteration   3: 3.610 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.463 ±(99.9%) 2.374 ms/op [Average]
  (min, avg, max) = (3.362, 3.463, 3.610), stdev = 0.130
  CI (99.9%): [1.089, 5.838] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.181 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.006 ms/op
Iteration   1: 3.231 ±(99.9%) 0.008 ms/op
Iteration   2: 3.225 ±(99.9%) 0.009 ms/op
Iteration   3: 3.222 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.226 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (3.222, 3.226, 3.231), stdev = 0.005
  CI (99.9%): [3.138, 3.314] (assumes normal distribution)


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
# Warmup Iteration   1: 9.026 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.002 ms/op
Iteration   1: 3.468 ±(99.9%) 0.004 ms/op
Iteration   2: 3.423 ±(99.9%) 0.008 ms/op
Iteration   3: 3.432 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.441 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.423, 3.441, 3.468), stdev = 0.024
  CI (99.9%): [3.008, 3.874] (assumes normal distribution)


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
# Warmup Iteration   1: 10.483 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.010 ms/op
Iteration   1: 4.047 ±(99.9%) 0.008 ms/op
Iteration   2: 4.063 ±(99.9%) 0.008 ms/op
Iteration   3: 3.937 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.015 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (3.937, 4.015, 4.063), stdev = 0.068
  CI (99.9%): [2.769, 5.262] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.803 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.011 ms/op
Iteration   1: 3.346 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  20.435 ms/op
                 createUser·p0.9999: 27.375 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   2: 3.356 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.660 ms/op
                 createUser·p0.999:  22.682 ms/op
                 createUser·p0.9999: 27.026 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 3.293 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  17.629 ms/op
                 createUser·p0.9999: 26.355 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288216
  mean =      3.331 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14308 
    [ 2.500,  5.000) = 268675 
    [ 5.000,  7.500) = 4377 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 127 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     27.889 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 8.739 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.501 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  11.698 ms/op
                 existUser·p0.9999: 22.332 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  11.000 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  10.774 ms/op
                 existUser·p0.9999: 25.142 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290901
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5696 
    [ 2.500,  5.000) = 279635 
    [ 5.000,  7.500) = 4592 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     24.016 ms/op
     p(99.9990) =     26.673 ms/op
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
# Warmup Iteration   1: 9.784 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.011 ms/op
Iteration   1: 3.439 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  19.005 ms/op
                 getUser·p0.9999: 22.142 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   2: 3.450 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  21.109 ms/op
                 getUser·p0.9999: 25.344 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.387 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 26.870 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280062
  mean =      3.425 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6751 
    [ 2.500,  5.000) = 265894 
    [ 5.000,  7.500) = 6189 
    [ 7.500, 10.000) = 764 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     19.397 ms/op
     p(99.9900) =     25.493 ms/op
     p(99.9990) =     27.355 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 11.684 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.015 ms/op
Iteration   1: 4.249 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  17.411 ms/op
                 listUser·p0.9999: 26.378 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 3.972 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.566 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 16.776 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 4.034 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.321 ms/op
                 listUser·p0.999:  15.413 ms/op
                 listUser·p0.9999: 18.262 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235007
  mean =      4.082 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 225357 
    [ 5.000,  7.500) = 7088 
    [ 7.500, 10.000) = 1851 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 210 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     26.898 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.263 ± 0.644  ops/ms
ClientPb.existUser                       thrpt       3   9.666 ± 0.664  ops/ms
ClientPb.getUser                         thrpt       3   9.370 ± 2.336  ops/ms
ClientPb.listUser                        thrpt       3   8.112 ± 1.349  ops/ms
ClientPb.createUser                       avgt       3   3.463 ± 2.374   ms/op
ClientPb.existUser                        avgt       3   3.226 ± 0.088   ms/op
ClientPb.getUser                          avgt       3   3.441 ± 0.433   ms/op
ClientPb.listUser                         avgt       3   4.015 ± 1.247   ms/op
ClientPb.createUser                     sample  288216   3.331 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.149           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.561           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.870           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.377           ms/op
ClientPb.existUser                      sample  290901   3.298 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.319           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.272           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.016           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  280062   3.425 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.171           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.397           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.493           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  235007   4.082 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.917           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.692           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.335           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.510           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
