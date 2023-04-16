# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 5.934 ops/ms
# Warmup Iteration   3: 9.232 ops/ms
Iteration   1: 9.787 ops/ms
Iteration   2: 9.728 ops/ms
Iteration   3: 9.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.810 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (9.728, 9.810, 9.915), stdev = 0.096
  CI (99.9%): [8.063, 11.557] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ops/ms
# Warmup Iteration   2: 9.555 ops/ms
# Warmup Iteration   3: 10.381 ops/ms
Iteration   1: 10.114 ops/ms
Iteration   2: 10.487 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.407 ±(99.9%) 4.787 ops/ms [Average]
  (min, avg, max) = (10.114, 10.407, 10.620), stdev = 0.262
  CI (99.9%): [5.620, 15.194] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 9.180 ops/ms
# Warmup Iteration   3: 9.822 ops/ms
Iteration   1: 10.336 ops/ms
Iteration   2: 10.420 ops/ms
Iteration   3: 10.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.319 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (10.202, 10.319, 10.420), stdev = 0.110
  CI (99.9%): [8.318, 12.320] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.209 ops/ms
# Warmup Iteration   2: 7.692 ops/ms
# Warmup Iteration   3: 8.284 ops/ms
Iteration   1: 8.534 ops/ms
Iteration   2: 8.460 ops/ms
Iteration   3: 8.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.562 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (8.460, 8.562, 8.692), stdev = 0.119
  CI (99.9%): [6.398, 10.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.919 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.006 ms/op
Iteration   1: 3.138 ±(99.9%) 0.005 ms/op
Iteration   2: 3.253 ±(99.9%) 0.007 ms/op
Iteration   3: 3.128 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.173 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (3.128, 3.173, 3.253), stdev = 0.070
  CI (99.9%): [1.900, 4.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.689 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.004 ms/op
Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
Iteration   3: 3.086 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.077 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (3.028, 3.077, 3.117), stdev = 0.045
  CI (99.9%): [2.252, 3.901] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.522 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.004 ms/op
Iteration   1: 3.175 ±(99.9%) 0.008 ms/op
Iteration   2: 3.231 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.159 ±(99.9%) 1.464 ms/op [Average]
  (min, avg, max) = (3.073, 3.159, 3.231), stdev = 0.080
  CI (99.9%): [1.695, 4.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.840 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.009 ms/op
Iteration   1: 3.717 ±(99.9%) 0.008 ms/op
Iteration   2: 3.626 ±(99.9%) 0.012 ms/op
Iteration   3: 3.712 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.685 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.626, 3.685, 3.717), stdev = 0.051
  CI (99.9%): [2.756, 4.615] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.742 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.008 ms/op
Iteration   1: 3.183 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  17.483 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  13.025 ms/op
                 createUser·p0.9999: 23.689 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  13.620 ms/op
                 createUser·p0.9999: 17.564 ms/op
                 createUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299706
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26652 
    [ 2.500,  5.000) = 265273 
    [ 5.000,  7.500) = 6737 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     24.085 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.214 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
Iteration   1: 3.151 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  11.618 ms/op
                 existUser·p0.9999: 28.344 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   2: 3.079 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 21.516 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.578 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308123
  mean =      3.113 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25342 
    [ 2.500,  5.000) = 277406 
    [ 5.000,  7.500) = 4606 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     26.778 ms/op
     p(99.9990) =     29.063 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.685 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
Iteration   1: 3.305 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.477 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 22.990 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.224 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  19.262 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   3: 3.758 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  19.363 ms/op
                 getUser·p0.9999: 31.310 ms/op
                 getUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281134
  mean =      3.413 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18850 
    [ 2.500,  5.000) = 244662 
    [ 5.000,  7.500) = 16019 
    [ 7.500, 10.000) = 1051 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     29.750 ms/op
     p(99.9990) =     32.425 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.598 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.011 ms/op
Iteration   1: 3.888 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 20.694 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.717 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   3: 3.831 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  12.190 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251965
  mean =      3.811 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 243187 
    [ 5.000,  7.500) = 6784 
    [ 7.500, 10.000) = 1212 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     21.090 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.810 ± 1.747  ops/ms
ClientPb.existUser                       thrpt       3  10.407 ± 4.787  ops/ms
ClientPb.getUser                         thrpt       3  10.319 ± 2.001  ops/ms
ClientPb.listUser                        thrpt       3   8.562 ± 2.164  ops/ms
ClientPb.createUser                       avgt       3   3.173 ± 1.272   ms/op
ClientPb.existUser                        avgt       3   3.077 ± 0.825   ms/op
ClientPb.getUser                          avgt       3   3.159 ± 1.464   ms/op
ClientPb.listUser                         avgt       3   3.685 ± 0.930   ms/op
ClientPb.createUser                     sample  299706   3.202 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.041           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.381           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.412           ms/op
ClientPb.existUser                      sample  308123   3.113 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.057           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.778           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.164           ms/op
ClientPb.getUser                        sample  281134   3.413 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.699           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.678           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.750           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.096           ms/op
ClientPb.listUser                       sample  251965   3.811 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.640           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.386           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.090           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.249           ms/op
