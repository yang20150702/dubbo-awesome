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
# Warmup Iteration   1: 1.222 ops/ms
# Warmup Iteration   2: 2.810 ops/ms
# Warmup Iteration   3: 5.626 ops/ms
Iteration   1: 5.710 ops/ms
Iteration   2: 5.989 ops/ms
Iteration   3: 5.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.855 ±(99.9%) 2.545 ops/ms [Average]
  (min, avg, max) = (5.710, 5.855, 5.989), stdev = 0.140
  CI (99.9%): [3.310, 8.400] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.761 ops/ms
# Warmup Iteration   2: 5.388 ops/ms
# Warmup Iteration   3: 6.017 ops/ms
Iteration   1: 6.349 ops/ms
Iteration   2: 6.073 ops/ms
Iteration   3: 6.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.150 ±(99.9%) 3.174 ops/ms [Average]
  (min, avg, max) = (6.028, 6.150, 6.349), stdev = 0.174
  CI (99.9%): [2.976, 9.324] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.683 ops/ms
# Warmup Iteration   2: 4.447 ops/ms
# Warmup Iteration   3: 5.520 ops/ms
Iteration   1: 5.510 ops/ms
Iteration   2: 5.478 ops/ms
Iteration   3: 5.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.641 ±(99.9%) 4.651 ops/ms [Average]
  (min, avg, max) = (5.478, 5.641, 5.935), stdev = 0.255
  CI (99.9%): [0.990, 10.292] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.743 ops/ms
# Warmup Iteration   2: 4.175 ops/ms
# Warmup Iteration   3: 4.980 ops/ms
Iteration   1: 4.684 ops/ms
Iteration   2: 4.920 ops/ms
Iteration   3: 5.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.883 ±(99.9%) 3.332 ops/ms [Average]
  (min, avg, max) = (4.684, 4.883, 5.044), stdev = 0.183
  CI (99.9%): [1.551, 8.215] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.426 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.280 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.960 ±(99.9%) 0.011 ms/op
Iteration   1: 5.694 ±(99.9%) 0.008 ms/op
Iteration   2: 5.492 ±(99.9%) 0.008 ms/op
Iteration   3: 5.606 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.597 ±(99.9%) 1.851 ms/op [Average]
  (min, avg, max) = (5.492, 5.597, 5.694), stdev = 0.101
  CI (99.9%): [3.746, 7.448] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.001 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.213 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.485 ±(99.9%) 0.004 ms/op
Iteration   1: 5.504 ±(99.9%) 0.006 ms/op
Iteration   2: 5.387 ±(99.9%) 0.008 ms/op
Iteration   3: 5.299 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.396 ±(99.9%) 1.883 ms/op [Average]
  (min, avg, max) = (5.299, 5.396, 5.504), stdev = 0.103
  CI (99.9%): [3.514, 7.279] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 19.488 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.691 ±(99.9%) 0.010 ms/op
Iteration   1: 5.705 ±(99.9%) 0.008 ms/op
Iteration   2: 5.700 ±(99.9%) 0.010 ms/op
Iteration   3: 5.521 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.642 ±(99.9%) 1.910 ms/op [Average]
  (min, avg, max) = (5.521, 5.642, 5.705), stdev = 0.105
  CI (99.9%): [3.732, 7.552] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.204 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 8.554 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.730 ±(99.9%) 0.011 ms/op
Iteration   1: 6.332 ±(99.9%) 0.009 ms/op
Iteration   2: 6.491 ±(99.9%) 0.011 ms/op
Iteration   3: 6.137 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.320 ±(99.9%) 3.235 ms/op [Average]
  (min, avg, max) = (6.137, 6.320, 6.491), stdev = 0.177
  CI (99.9%): [3.085, 9.555] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.401 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.618 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.796 ±(99.9%) 0.021 ms/op
Iteration   1: 5.478 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.898 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.209 ms/op
                 createUser·p0.99:   9.966 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 25.237 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   2: 5.427 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.179 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.513 ms/op
                 createUser·p0.95:   7.356 ms/op
                 createUser·p0.99:   11.272 ms/op
                 createUser·p0.999:  21.825 ms/op
                 createUser·p0.9999: 26.251 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 5.417 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   10.076 ms/op
                 createUser·p0.999:  21.856 ms/op
                 createUser·p0.9999: 32.444 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176332
  mean =      5.441 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 71025 
    [ 5.000,  7.500) = 96695 
    [ 7.500, 10.000) = 6655 
    [10.000, 12.500) = 1148 
    [12.500, 15.000) = 383 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     29.515 ms/op
     p(99.9990) =     32.635 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.460 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.602 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.241 ±(99.9%) 0.017 ms/op
Iteration   1: 5.126 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   7.307 ms/op
                 existUser·p0.99:   10.224 ms/op
                 existUser·p0.999:  23.745 ms/op
                 existUser·p0.9999: 27.167 ms/op
                 existUser·p1.00:   30.671 ms/op

Iteration   2: 5.105 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.253 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   6.767 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  22.577 ms/op
                 existUser·p0.9999: 26.435 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 5.354 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.791 ms/op
                 existUser·p0.99:   13.943 ms/op
                 existUser·p0.999:  21.791 ms/op
                 existUser·p0.9999: 28.385 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184777
  mean =      5.193 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 103830 
    [ 5.000,  7.500) = 72904 
    [ 7.500, 10.000) = 5556 
    [10.000, 12.500) = 1186 
    [12.500, 15.000) = 536 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.301 ms/op
     p(95.0000) =      7.250 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     22.213 ms/op
     p(99.9900) =     26.985 ms/op
     p(99.9990) =     30.791 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.475 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.292 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.539 ±(99.9%) 0.017 ms/op
Iteration   1: 5.513 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   6.767 ms/op
                 getUser·p0.95:   7.487 ms/op
                 getUser·p0.99:   9.945 ms/op
                 getUser·p0.999:  19.661 ms/op
                 getUser·p0.9999: 23.213 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 5.781 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.318 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.111 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   12.386 ms/op
                 getUser·p0.999:  22.043 ms/op
                 getUser·p0.9999: 26.802 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 5.332 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.062 ms/op
                 getUser·p0.99:   9.552 ms/op
                 getUser·p0.999:  22.023 ms/op
                 getUser·p0.9999: 31.326 ms/op
                 getUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173266
  mean =      5.536 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 63143 
    [ 5.000,  7.500) = 100579 
    [ 7.500, 10.000) = 7160 
    [10.000, 12.500) = 1522 
    [12.500, 15.000) = 455 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     30.782 ms/op
     p(99.9990) =     31.868 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.621 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 7.521 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.637 ±(99.9%) 0.022 ms/op
Iteration   1: 6.339 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  25.037 ms/op
                 listUser·p0.9999: 27.912 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   2: 6.520 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.035 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   13.072 ms/op
                 listUser·p0.999:  27.590 ms/op
                 listUser·p0.9999: 30.127 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   3: 6.326 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.578 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.816 ms/op
                 listUser·p0.999:  21.477 ms/op
                 listUser·p0.9999: 30.860 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150058
  mean =      6.394 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 5863 
    [ 5.000,  7.500) = 129340 
    [ 7.500, 10.000) = 11035 
    [10.000, 12.500) = 2452 
    [12.500, 15.000) = 700 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      6.111 ms/op
     p(90.0000) =      7.487 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     12.157 ms/op
     p(99.9000) =     25.885 ms/op
     p(99.9900) =     30.113 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.855 ± 2.545  ops/ms
ClientPb.existUser                       thrpt       3   6.150 ± 3.174  ops/ms
ClientPb.getUser                         thrpt       3   5.641 ± 4.651  ops/ms
ClientPb.listUser                        thrpt       3   4.883 ± 3.332  ops/ms
ClientPb.createUser                       avgt       3   5.597 ± 1.851   ms/op
ClientPb.existUser                        avgt       3   5.396 ± 1.883   ms/op
ClientPb.getUser                          avgt       3   5.642 ± 1.910   ms/op
ClientPb.listUser                         avgt       3   6.320 ± 3.235   ms/op
ClientPb.createUser                     sample  176332   5.441 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.779           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.169           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.652           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.463           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.306           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.251           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.515           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.735           ms/op
ClientPb.existUser                      sample  184777   5.193 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.421           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.879           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.213           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.985           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.457           ms/op
ClientPb.getUser                        sample  173266   5.536 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.673           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.551           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.201           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.782           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.916           ms/op
ClientPb.listUser                       sample  150058   6.394 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.111           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.487           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.157           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.885           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.113           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.195           ms/op
