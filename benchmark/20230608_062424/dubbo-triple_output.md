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
# Warmup Iteration   1: 1.373 ops/ms
# Warmup Iteration   2: 3.199 ops/ms
# Warmup Iteration   3: 5.905 ops/ms
Iteration   1: 6.167 ops/ms
Iteration   2: 6.552 ops/ms
Iteration   3: 6.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.404 ±(99.9%) 3.786 ops/ms [Average]
  (min, avg, max) = (6.167, 6.404, 6.552), stdev = 0.208
  CI (99.9%): [2.618, 10.191] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.739 ops/ms
# Warmup Iteration   2: 5.162 ops/ms
# Warmup Iteration   3: 6.590 ops/ms
Iteration   1: 6.316 ops/ms
Iteration   2: 6.494 ops/ms
Iteration   3: 6.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.586 ±(99.9%) 5.947 ops/ms [Average]
  (min, avg, max) = (6.316, 6.586, 6.948), stdev = 0.326
  CI (99.9%): [0.639, 12.532] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.486 ops/ms
# Warmup Iteration   2: 3.925 ops/ms
# Warmup Iteration   3: 5.840 ops/ms
Iteration   1: 5.971 ops/ms
Iteration   2: 5.931 ops/ms
Iteration   3: 6.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.000 ±(99.9%) 1.599 ops/ms [Average]
  (min, avg, max) = (5.931, 6.000, 6.099), stdev = 0.088
  CI (99.9%): [4.401, 7.599] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.568 ops/ms
# Warmup Iteration   2: 4.755 ops/ms
# Warmup Iteration   3: 5.038 ops/ms
Iteration   1: 5.259 ops/ms
Iteration   2: 5.340 ops/ms
Iteration   3: 5.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.269 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (5.208, 5.269, 5.340), stdev = 0.067
  CI (99.9%): [4.054, 6.484] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 17.824 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.345 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.452 ±(99.9%) 0.014 ms/op
Iteration   1: 5.364 ±(99.9%) 0.011 ms/op
Iteration   2: 5.203 ±(99.9%) 0.006 ms/op
Iteration   3: 5.257 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.275 ±(99.9%) 1.498 ms/op [Average]
  (min, avg, max) = (5.203, 5.275, 5.364), stdev = 0.082
  CI (99.9%): [3.777, 6.773] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.177 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.825 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.127 ±(99.9%) 0.010 ms/op
Iteration   1: 5.116 ±(99.9%) 0.005 ms/op
Iteration   2: 5.321 ±(99.9%) 0.007 ms/op
Iteration   3: 5.419 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.285 ±(99.9%) 2.825 ms/op [Average]
  (min, avg, max) = (5.116, 5.285, 5.419), stdev = 0.155
  CI (99.9%): [2.460, 8.110] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.515 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.365 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.770 ±(99.9%) 0.007 ms/op
Iteration   1: 5.471 ±(99.9%) 0.006 ms/op
Iteration   2: 5.087 ±(99.9%) 0.016 ms/op
Iteration   3: 4.946 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.168 ±(99.9%) 4.958 ms/op [Average]
  (min, avg, max) = (4.946, 5.168, 5.471), stdev = 0.272
  CI (99.9%): [0.210, 10.126] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.296 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.396 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.788 ±(99.9%) 0.016 ms/op
Iteration   1: 5.626 ±(99.9%) 0.020 ms/op
Iteration   2: 5.473 ±(99.9%) 0.018 ms/op
Iteration   3: 5.856 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.652 ±(99.9%) 3.523 ms/op [Average]
  (min, avg, max) = (5.473, 5.652, 5.856), stdev = 0.193
  CI (99.9%): [2.129, 9.175] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.663 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.980 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.024 ms/op
Iteration   1: 4.996 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   7.008 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  21.381 ms/op
                 createUser·p0.9999: 26.857 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 4.954 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   4.710 ms/op
                 createUser·p0.90:   6.054 ms/op
                 createUser·p0.95:   6.668 ms/op
                 createUser·p0.99:   8.249 ms/op
                 createUser·p0.999:  24.295 ms/op
                 createUser·p0.9999: 27.528 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 5.159 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   4.874 ms/op
                 createUser·p0.90:   6.357 ms/op
                 createUser·p0.95:   7.365 ms/op
                 createUser·p0.99:   10.162 ms/op
                 createUser·p0.999:  24.446 ms/op
                 createUser·p0.9999: 28.967 ms/op
                 createUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 190590
  mean =      5.035 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 118792 
    [ 5.000,  7.500) = 65331 
    [ 7.500, 10.000) = 5159 
    [10.000, 12.500) = 755 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 97 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      6.955 ms/op
     p(99.0000) =      9.273 ms/op
     p(99.9000) =     23.770 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     29.560 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.088 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.271 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.153 ±(99.9%) 0.020 ms/op
Iteration   1: 4.903 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.044 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   6.177 ms/op
                 existUser·p0.95:   6.767 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  14.289 ms/op
                 existUser·p0.9999: 27.213 ms/op
                 existUser·p1.00:   28.312 ms/op

Iteration   2: 4.887 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.097 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   9.291 ms/op
                 existUser·p0.999:  17.204 ms/op
                 existUser·p0.9999: 25.641 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 4.948 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.097 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   6.758 ms/op
                 existUser·p0.99:   9.028 ms/op
                 existUser·p0.999:  18.447 ms/op
                 existUser·p0.9999: 31.727 ms/op
                 existUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195407
  mean =      4.912 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 130652 
    [ 5.000,  7.500) = 59381 
    [ 7.500, 10.000) = 4254 
    [10.000, 12.500) = 639 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.044 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     29.060 ms/op
     p(99.9990) =     32.448 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.598 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.459 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.952 ±(99.9%) 0.016 ms/op
Iteration   1: 5.084 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.327 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.169 ms/op
                 getUser·p0.95:   6.955 ms/op
                 getUser·p0.99:   10.174 ms/op
                 getUser·p0.999:  19.993 ms/op
                 getUser·p0.9999: 24.637 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   2: 4.903 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.905 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   6.054 ms/op
                 getUser·p0.95:   6.873 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  26.613 ms/op
                 getUser·p0.9999: 35.914 ms/op
                 getUser·p1.00:   44.499 ms/op

Iteration   3: 4.924 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   4.719 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.545 ms/op
                 getUser·p0.99:   9.025 ms/op
                 getUser·p0.999:  17.915 ms/op
                 getUser·p0.9999: 29.101 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 192986
  mean =      4.969 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 125273 
    [ 5.000, 10.000) = 66117 
    [10.000, 15.000) = 1172 
    [15.000, 20.000) = 140 
    [20.000, 25.000) = 138 
    [25.000, 30.000) = 97 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.905 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     33.545 ms/op
     p(99.9990) =     40.843 ms/op
     p(99.9999) =     44.499 ms/op
    p(100.0000) =     44.499 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.293 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 6.817 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.922 ±(99.9%) 0.024 ms/op
Iteration   1: 5.955 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  27.043 ms/op
                 listUser·p0.9999: 34.137 ms/op
                 listUser·p1.00:   35.062 ms/op

Iteration   2: 5.588 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.691 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  24.658 ms/op
                 listUser·p0.9999: 35.622 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   3: 5.660 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   5.439 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  19.807 ms/op
                 listUser·p0.9999: 23.146 ms/op
                 listUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 167496
  mean =      5.730 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 35895 
    [ 5.000,  7.500) = 121617 
    [ 7.500, 10.000) = 7902 
    [10.000, 12.500) = 1494 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      5.480 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.782 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     23.970 ms/op
     p(99.9900) =     34.914 ms/op
     p(99.9990) =     36.699 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.404 ± 3.786  ops/ms
ClientPb.existUser                       thrpt       3   6.586 ± 5.947  ops/ms
ClientPb.getUser                         thrpt       3   6.000 ± 1.599  ops/ms
ClientPb.listUser                        thrpt       3   5.269 ± 1.215  ops/ms
ClientPb.createUser                       avgt       3   5.275 ± 1.498   ms/op
ClientPb.existUser                        avgt       3   5.285 ± 2.825   ms/op
ClientPb.getUser                          avgt       3   5.168 ± 4.958   ms/op
ClientPb.listUser                         avgt       3   5.652 ± 3.523   ms/op
ClientPb.createUser                     sample  190590   5.035 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.477           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.955           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.273           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.770           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.886           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.590           ms/op
ClientPb.existUser                      sample  195407   4.912 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.840           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.831           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.138           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.060           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.604           ms/op
ClientPb.getUser                        sample  192986   4.969 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.905           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.183           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.545           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.499           ms/op
ClientPb.listUser                       sample  167496   5.730 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.411           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.782           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.970           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.914           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.831           ms/op
