# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.064 ops/ms
# Warmup Iteration   2: 4.668 ops/ms
# Warmup Iteration   3: 8.929 ops/ms
Iteration   1: 9.374 ops/ms
Iteration   2: 9.176 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.336 ±(99.9%) 2.644 ops/ms [Average]
  (min, avg, max) = (9.176, 9.336, 9.459), stdev = 0.145
  CI (99.9%): [6.692, 11.980] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.805 ops/ms
# Warmup Iteration   2: 8.649 ops/ms
# Warmup Iteration   3: 9.723 ops/ms
Iteration   1: 9.744 ops/ms
Iteration   2: 9.611 ops/ms
Iteration   3: 9.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.713 ±(99.9%) 1.664 ops/ms [Average]
  (min, avg, max) = (9.611, 9.713, 9.785), stdev = 0.091
  CI (99.9%): [8.049, 11.378] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.756 ops/ms
# Warmup Iteration   2: 8.259 ops/ms
# Warmup Iteration   3: 9.090 ops/ms
Iteration   1: 9.343 ops/ms
Iteration   2: 9.378 ops/ms
Iteration   3: 9.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.365 ±(99.9%) 0.360 ops/ms [Average]
  (min, avg, max) = (9.343, 9.365, 9.378), stdev = 0.020
  CI (99.9%): [9.005, 9.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.911 ops/ms
# Warmup Iteration   2: 7.507 ops/ms
# Warmup Iteration   3: 8.085 ops/ms
Iteration   1: 8.045 ops/ms
Iteration   2: 8.120 ops/ms
Iteration   3: 7.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.023 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (7.905, 8.023, 8.120), stdev = 0.109
  CI (99.9%): [6.034, 10.012] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.689 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.003 ms/op
Iteration   1: 3.375 ±(99.9%) 0.006 ms/op
Iteration   2: 3.340 ±(99.9%) 0.012 ms/op
Iteration   3: 3.474 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.396 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (3.340, 3.396, 3.474), stdev = 0.069
  CI (99.9%): [2.130, 4.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.426 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.004 ms/op
Iteration   1: 3.155 ±(99.9%) 0.009 ms/op
Iteration   2: 3.303 ±(99.9%) 0.005 ms/op
Iteration   3: 3.263 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.240 ±(99.9%) 1.398 ms/op [Average]
  (min, avg, max) = (3.155, 3.240, 3.303), stdev = 0.077
  CI (99.9%): [1.843, 4.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.752 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.004 ms/op
Iteration   1: 3.471 ±(99.9%) 0.006 ms/op
Iteration   2: 3.487 ±(99.9%) 0.004 ms/op
Iteration   3: 3.400 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.453 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (3.400, 3.453, 3.487), stdev = 0.046
  CI (99.9%): [2.607, 4.298] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.519 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.008 ms/op
Iteration   1: 4.207 ±(99.9%) 0.010 ms/op
Iteration   2: 3.967 ±(99.9%) 0.012 ms/op
Iteration   3: 4.069 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.081 ±(99.9%) 2.192 ms/op [Average]
  (min, avg, max) = (3.967, 4.081, 4.207), stdev = 0.120
  CI (99.9%): [1.889, 6.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.219 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.011 ms/op
Iteration   1: 3.569 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  21.964 ms/op
                 createUser·p0.9999: 30.053 ms/op
                 createUser·p1.00:   30.966 ms/op

Iteration   2: 3.383 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  23.822 ms/op
                 createUser·p0.9999: 26.083 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.414 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  17.072 ms/op
                 createUser·p0.9999: 28.267 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277904
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15414 
    [ 2.500,  5.000) = 251902 
    [ 5.000,  7.500) = 9099 
    [ 7.500, 10.000) = 771 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     17.280 ms/op
     p(99.9900) =     29.367 ms/op
     p(99.9990) =     30.540 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.298 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.009 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  10.458 ms/op
                 existUser·p0.9999: 27.169 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  10.416 ms/op
                 existUser·p0.9999: 30.840 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  13.861 ms/op
                 existUser·p0.9999: 28.672 ms/op
                 existUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296526
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8951 
    [ 2.500,  5.000) = 282319 
    [ 5.000,  7.500) = 4168 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     30.387 ms/op
     p(99.9990) =     31.237 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.931 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.012 ms/op
Iteration   1: 3.461 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 25.190 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   2: 3.391 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  12.484 ms/op
                 getUser·p0.9999: 26.317 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   3: 3.620 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  19.454 ms/op
                 getUser·p0.9999: 28.612 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275243
  mean =      3.488 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4129 
    [ 2.500,  5.000) = 264034 
    [ 5.000,  7.500) = 5854 
    [ 7.500, 10.000) = 646 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     18.539 ms/op
     p(99.9900) =     27.622 ms/op
     p(99.9990) =     29.221 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.177 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.540 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.014 ms/op
Iteration   1: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  21.986 ms/op
                 listUser·p0.9999: 29.464 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   2: 3.967 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.905 ms/op
                 listUser·p0.999:  18.559 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239046
  mean =      4.014 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 230805 
    [ 5.000,  7.500) = 5678 
    [ 7.500, 10.000) = 1513 
    [10.000, 12.500) = 449 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.835 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     18.709 ms/op
     p(99.9900) =     25.693 ms/op
     p(99.9990) =     29.708 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.336 ± 2.644  ops/ms
ClientPb.existUser                       thrpt       3   9.713 ± 1.664  ops/ms
ClientPb.getUser                         thrpt       3   9.365 ± 0.360  ops/ms
ClientPb.listUser                        thrpt       3   8.023 ± 1.989  ops/ms
ClientPb.createUser                       avgt       3   3.396 ± 1.267   ms/op
ClientPb.existUser                        avgt       3   3.240 ± 1.398   ms/op
ClientPb.getUser                          avgt       3   3.453 ± 0.846   ms/op
ClientPb.listUser                         avgt       3   4.081 ± 2.192   ms/op
ClientPb.createUser                     sample  277904   3.453 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.337           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.280           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.367           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.966           ms/op
ClientPb.existUser                      sample  296526   3.235 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.272           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.631           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.387           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.654           ms/op
ClientPb.getUser                        sample  275243   3.488 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.539           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.622           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.950           ms/op
ClientPb.listUser                       sample  239046   4.014 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.835           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.643           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.709           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.693           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.179           ms/op
