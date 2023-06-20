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
# Warmup Iteration   1: 1.854 ops/ms
# Warmup Iteration   2: 5.061 ops/ms
# Warmup Iteration   3: 7.894 ops/ms
Iteration   1: 8.848 ops/ms
Iteration   2: 8.637 ops/ms
Iteration   3: 8.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.768 ±(99.9%) 2.092 ops/ms [Average]
  (min, avg, max) = (8.637, 8.768, 8.848), stdev = 0.115
  CI (99.9%): [6.677, 10.860] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.924 ops/ms
# Warmup Iteration   2: 8.642 ops/ms
# Warmup Iteration   3: 9.108 ops/ms
Iteration   1: 9.519 ops/ms
Iteration   2: 9.204 ops/ms
Iteration   3: 9.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.358 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (9.204, 9.358, 9.519), stdev = 0.158
  CI (99.9%): [6.481, 12.236] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.435 ops/ms
# Warmup Iteration   2: 6.561 ops/ms
# Warmup Iteration   3: 8.509 ops/ms
Iteration   1: 8.986 ops/ms
Iteration   2: 9.026 ops/ms
Iteration   3: 8.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.951 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (8.841, 8.951, 9.026), stdev = 0.097
  CI (99.9%): [7.176, 10.726] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.232 ops/ms
# Warmup Iteration   2: 6.713 ops/ms
# Warmup Iteration   3: 7.396 ops/ms
Iteration   1: 7.634 ops/ms
Iteration   2: 7.494 ops/ms
Iteration   3: 7.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.552 ±(99.9%) 1.324 ops/ms [Average]
  (min, avg, max) = (7.494, 7.552, 7.634), stdev = 0.073
  CI (99.9%): [6.228, 8.876] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.974 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.006 ms/op
Iteration   1: 3.580 ±(99.9%) 0.007 ms/op
Iteration   2: 3.596 ±(99.9%) 0.006 ms/op
Iteration   3: 3.545 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.574 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.545, 3.574, 3.596), stdev = 0.026
  CI (99.9%): [3.098, 4.050] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.499 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
Iteration   1: 3.426 ±(99.9%) 0.012 ms/op
Iteration   2: 3.334 ±(99.9%) 0.009 ms/op
Iteration   3: 3.357 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.372 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (3.334, 3.372, 3.426), stdev = 0.048
  CI (99.9%): [2.505, 4.240] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.219 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.007 ms/op
Iteration   1: 3.816 ±(99.9%) 0.007 ms/op
Iteration   2: 3.683 ±(99.9%) 0.006 ms/op
Iteration   3: 3.507 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.669 ±(99.9%) 2.826 ms/op [Average]
  (min, avg, max) = (3.507, 3.669, 3.816), stdev = 0.155
  CI (99.9%): [0.843, 6.494] (assumes normal distribution)


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
# Warmup Iteration   1: 12.779 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.874 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.391 ±(99.9%) 0.006 ms/op
Iteration   1: 4.207 ±(99.9%) 0.010 ms/op
Iteration   2: 4.235 ±(99.9%) 0.008 ms/op
Iteration   3: 4.255 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.232 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (4.207, 4.232, 4.255), stdev = 0.024
  CI (99.9%): [3.794, 4.670] (assumes normal distribution)


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
# Warmup Iteration   1: 11.182 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.016 ms/op
Iteration   1: 3.605 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  21.019 ms/op
                 createUser·p0.9999: 27.558 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 3.602 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  23.276 ms/op
                 createUser·p0.9999: 25.530 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.557 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.186 ms/op
                 createUser·p0.999:  23.757 ms/op
                 createUser·p0.9999: 30.376 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267589
  mean =      3.588 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1981 
    [ 2.500,  5.000) = 257498 
    [ 5.000,  7.500) = 6848 
    [ 7.500, 10.000) = 768 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     22.381 ms/op
     p(99.9900) =     29.368 ms/op
     p(99.9990) =     31.796 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 9.686 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.009 ms/op
Iteration   1: 3.638 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  20.972 ms/op
                 existUser·p0.9999: 24.382 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   2: 3.583 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  14.238 ms/op
                 existUser·p0.9999: 25.919 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  23.481 ms/op
                 existUser·p0.9999: 29.684 ms/op
                 existUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 267561
  mean =      3.588 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5223 
    [ 2.500,  5.000) = 251324 
    [ 5.000,  7.500) = 9547 
    [ 7.500, 10.000) = 896 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     27.926 ms/op
     p(99.9990) =     30.299 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 12.506 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.014 ms/op
Iteration   1: 3.654 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.186 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  21.315 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   2: 3.645 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.829 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  23.359 ms/op
                 getUser·p0.9999: 30.638 ms/op
                 getUser·p1.00:   31.621 ms/op

Iteration   3: 3.655 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  26.690 ms/op
                 getUser·p0.9999: 34.308 ms/op
                 getUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262734
  mean =      3.651 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3060 
    [ 2.500,  5.000) = 250528 
    [ 5.000,  7.500) = 7188 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     21.636 ms/op
     p(99.9900) =     33.414 ms/op
     p(99.9990) =     35.479 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 13.750 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 5.069 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.601 ±(99.9%) 0.018 ms/op
Iteration   1: 4.289 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  23.958 ms/op
                 listUser·p0.9999: 27.066 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   2: 4.136 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  16.155 ms/op
                 listUser·p0.9999: 19.112 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 4.204 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 17.098 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227780
  mean =      4.209 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 217897 
    [ 5.000,  7.500) = 6765 
    [ 7.500, 10.000) = 2079 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.862 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     16.433 ms/op
     p(99.9900) =     26.058 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.768 ± 2.092  ops/ms
ClientPb.existUser                       thrpt       3   9.358 ± 2.877  ops/ms
ClientPb.getUser                         thrpt       3   8.951 ± 1.775  ops/ms
ClientPb.listUser                        thrpt       3   7.552 ± 1.324  ops/ms
ClientPb.createUser                       avgt       3   3.574 ± 0.476   ms/op
ClientPb.existUser                        avgt       3   3.372 ± 0.867   ms/op
ClientPb.getUser                          avgt       3   3.669 ± 2.826   ms/op
ClientPb.listUser                         avgt       3   4.232 ± 0.438   ms/op
ClientPb.createUser                     sample  267589   3.588 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.332           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.381           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.368           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  267561   3.588 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.931           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.824           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.926           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.409           ms/op
ClientPb.getUser                        sample  262734   3.651 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.047           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.514           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.636           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.414           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  227780   4.209 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.907           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.036           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.433           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.058           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.886           ms/op
