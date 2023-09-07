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
# Warmup Iteration   1: 1.514 ops/ms
# Warmup Iteration   2: 4.638 ops/ms
# Warmup Iteration   3: 6.963 ops/ms
Iteration   1: 7.055 ops/ms
Iteration   2: 6.997 ops/ms
Iteration   3: 6.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.985 ±(99.9%) 1.381 ops/ms [Average]
  (min, avg, max) = (6.905, 6.985, 7.055), stdev = 0.076
  CI (99.9%): [5.605, 8.366] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.306 ops/ms
# Warmup Iteration   2: 6.347 ops/ms
# Warmup Iteration   3: 6.718 ops/ms
Iteration   1: 6.934 ops/ms
Iteration   2: 6.935 ops/ms
Iteration   3: 7.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.043 ±(99.9%) 3.446 ops/ms [Average]
  (min, avg, max) = (6.934, 7.043, 7.261), stdev = 0.189
  CI (99.9%): [3.598, 10.489] (assumes normal distribution)


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
# Warmup Iteration   1: 2.296 ops/ms
# Warmup Iteration   2: 6.565 ops/ms
# Warmup Iteration   3: 7.176 ops/ms
Iteration   1: 7.201 ops/ms
Iteration   2: 7.460 ops/ms
Iteration   3: 7.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.259 ±(99.9%) 3.286 ops/ms [Average]
  (min, avg, max) = (7.114, 7.259, 7.460), stdev = 0.180
  CI (99.9%): [3.973, 10.545] (assumes normal distribution)


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
# Warmup Iteration   1: 2.266 ops/ms
# Warmup Iteration   2: 5.820 ops/ms
# Warmup Iteration   3: 6.248 ops/ms
Iteration   1: 6.125 ops/ms
Iteration   2: 6.617 ops/ms
Iteration   3: 6.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.301 ±(99.9%) 4.995 ops/ms [Average]
  (min, avg, max) = (6.125, 6.301, 6.617), stdev = 0.274
  CI (99.9%): [1.306, 11.297] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.761 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.911 ±(99.9%) 0.008 ms/op
Iteration   1: 4.574 ±(99.9%) 0.008 ms/op
Iteration   2: 4.530 ±(99.9%) 0.013 ms/op
Iteration   3: 5.083 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.729 ±(99.9%) 5.603 ms/op [Average]
  (min, avg, max) = (4.530, 4.729, 5.083), stdev = 0.307
  CI (99.9%): [≈ 0, 10.333] (assumes normal distribution)


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
# Warmup Iteration   1: 14.094 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.173 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.674 ±(99.9%) 0.007 ms/op
Iteration   1: 4.245 ±(99.9%) 0.006 ms/op
Iteration   2: 4.136 ±(99.9%) 0.009 ms/op
Iteration   3: 4.256 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.213 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (4.136, 4.213, 4.256), stdev = 0.066
  CI (99.9%): [3.004, 5.421] (assumes normal distribution)


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
# Warmup Iteration   1: 11.534 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.398 ±(99.9%) 0.011 ms/op
Iteration   1: 4.345 ±(99.9%) 0.012 ms/op
Iteration   2: 4.488 ±(99.9%) 0.006 ms/op
Iteration   3: 4.313 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.382 ±(99.9%) 1.696 ms/op [Average]
  (min, avg, max) = (4.313, 4.382, 4.488), stdev = 0.093
  CI (99.9%): [2.686, 6.078] (assumes normal distribution)


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
# Warmup Iteration   1: 12.354 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.045 ±(99.9%) 0.013 ms/op
Iteration   1: 5.301 ±(99.9%) 0.011 ms/op
Iteration   2: 5.467 ±(99.9%) 0.011 ms/op
Iteration   3: 5.600 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.456 ±(99.9%) 2.737 ms/op [Average]
  (min, avg, max) = (5.301, 5.456, 5.600), stdev = 0.150
  CI (99.9%): [2.719, 8.193] (assumes normal distribution)


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
# Warmup Iteration   1: 13.812 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.411 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.280 ±(99.9%) 0.022 ms/op
Iteration   1: 4.743 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.537 ms/op
                 createUser·p0.99:   8.978 ms/op
                 createUser·p0.999:  13.601 ms/op
                 createUser·p0.9999: 24.218 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 4.750 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.786 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.874 ms/op
                 createUser·p0.95:   6.767 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  14.899 ms/op
                 createUser·p0.9999: 27.182 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   3: 4.785 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   4.530 ms/op
                 createUser·p0.90:   5.865 ms/op
                 createUser·p0.95:   6.529 ms/op
                 createUser·p0.99:   9.110 ms/op
                 createUser·p0.999:  16.220 ms/op
                 createUser·p0.9999: 31.216 ms/op
                 createUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 201562
  mean =      4.759 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 144282 
    [ 5.000,  7.500) = 52028 
    [ 7.500, 10.000) = 3839 
    [10.000, 12.500) = 810 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.636 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     16.012 ms/op
     p(99.9900) =     29.743 ms/op
     p(99.9990) =     32.046 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 13.773 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.172 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.477 ±(99.9%) 0.015 ms/op
Iteration   1: 4.399 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   4.178 ms/op
                 existUser·p0.90:   5.497 ms/op
                 existUser·p0.95:   6.095 ms/op
                 existUser·p0.99:   7.799 ms/op
                 existUser·p0.999:  12.295 ms/op
                 existUser·p0.9999: 24.895 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 4.352 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   4.153 ms/op
                 existUser·p0.90:   5.284 ms/op
                 existUser·p0.95:   5.931 ms/op
                 existUser·p0.99:   8.471 ms/op
                 existUser·p0.999:  13.919 ms/op
                 existUser·p0.9999: 29.795 ms/op
                 existUser·p1.00:   32.047 ms/op

Iteration   3: 4.265 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.972 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.235 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   8.967 ms/op
                 existUser·p0.999:  19.431 ms/op
                 existUser·p0.9999: 25.395 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 221237
  mean =      4.338 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181 
    [ 2.500,  5.000) = 188009 
    [ 5.000,  7.500) = 29260 
    [ 7.500, 10.000) = 2650 
    [10.000, 12.500) = 738 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     17.589 ms/op
     p(99.9900) =     29.127 ms/op
     p(99.9990) =     31.769 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 14.479 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.506 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.068 ±(99.9%) 0.020 ms/op
Iteration   1: 4.907 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.367 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   7.332 ms/op
                 getUser·p0.99:   10.093 ms/op
                 getUser·p0.999:  20.939 ms/op
                 getUser·p0.9999: 27.622 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 4.427 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  23.134 ms/op
                 getUser·p0.9999: 25.643 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 4.204 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.780 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  12.631 ms/op
                 getUser·p0.9999: 26.063 ms/op
                 getUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 213522
  mean =      4.494 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 174309 
    [ 5.000,  7.500) = 34106 
    [ 7.500, 10.000) = 3824 
    [10.000, 12.500) = 833 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     21.085 ms/op
     p(99.9900) =     26.126 ms/op
     p(99.9990) =     27.971 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 13.227 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.442 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.273 ±(99.9%) 0.019 ms/op
Iteration   1: 5.215 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  25.909 ms/op
                 listUser·p0.9999: 28.941 ms/op
                 listUser·p1.00:   29.721 ms/op

Iteration   2: 5.169 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   7.217 ms/op
                 listUser·p0.99:   9.994 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 20.861 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 5.017 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  17.307 ms/op
                 listUser·p0.9999: 18.837 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 186991
  mean =      5.132 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 110939 
    [ 5.000,  7.500) = 68114 
    [ 7.500, 10.000) = 6180 
    [10.000, 12.500) = 1205 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     28.256 ms/op
     p(99.9990) =     29.664 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.985 ± 1.381  ops/ms
ClientPb.existUser                       thrpt       3   7.043 ± 3.446  ops/ms
ClientPb.getUser                         thrpt       3   7.259 ± 3.286  ops/ms
ClientPb.listUser                        thrpt       3   6.301 ± 4.995  ops/ms
ClientPb.createUser                       avgt       3   4.729 ± 5.603   ms/op
ClientPb.existUser                        avgt       3   4.213 ± 1.209   ms/op
ClientPb.getUser                          avgt       3   4.382 ± 1.696   ms/op
ClientPb.listUser                         avgt       3   5.456 ± 2.737   ms/op
ClientPb.createUser                     sample  201562   4.759 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.348           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.636           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.060           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.012           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.743           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.539           ms/op
ClientPb.existUser                      sample  221237   4.338 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.509           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.013           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.471           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.589           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.127           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.047           ms/op
ClientPb.getUser                        sample  213522   4.494 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.712           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.995           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.085           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.126           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.443           ms/op
ClientPb.listUser                       sample  186991   5.132 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.236           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.152           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.814           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.038           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.721           ms/op
