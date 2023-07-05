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
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 6.930 ops/ms
# Warmup Iteration   3: 9.416 ops/ms
Iteration   1: 9.451 ops/ms
Iteration   2: 9.635 ops/ms
Iteration   3: 9.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.592 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (9.451, 9.592, 9.689), stdev = 0.125
  CI (99.9%): [7.318, 11.865] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.502 ops/ms
# Warmup Iteration   2: 8.948 ops/ms
# Warmup Iteration   3: 10.076 ops/ms
Iteration   1: 10.284 ops/ms
Iteration   2: 10.442 ops/ms
Iteration   3: 10.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.290 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (10.143, 10.290, 10.442), stdev = 0.150
  CI (99.9%): [7.560, 13.019] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ops/ms
# Warmup Iteration   2: 9.100 ops/ms
# Warmup Iteration   3: 10.081 ops/ms
Iteration   1: 10.037 ops/ms
Iteration   2: 9.969 ops/ms
Iteration   3: 9.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.862 ±(99.9%) 4.509 ops/ms [Average]
  (min, avg, max) = (9.579, 9.862, 10.037), stdev = 0.247
  CI (99.9%): [5.353, 14.371] (assumes normal distribution)


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
# Warmup Iteration   1: 3.561 ops/ms
# Warmup Iteration   2: 7.705 ops/ms
# Warmup Iteration   3: 8.453 ops/ms
Iteration   1: 8.684 ops/ms
Iteration   2: 8.720 ops/ms
Iteration   3: 8.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.727 ±(99.9%) 0.853 ops/ms [Average]
  (min, avg, max) = (8.684, 8.727, 8.777), stdev = 0.047
  CI (99.9%): [7.873, 9.580] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.605 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.003 ms/op
Iteration   1: 3.175 ±(99.9%) 0.007 ms/op
Iteration   2: 3.208 ±(99.9%) 0.005 ms/op
Iteration   3: 3.156 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.180 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (3.156, 3.180, 3.208), stdev = 0.026
  CI (99.9%): [2.698, 3.661] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.005 ms/op
Iteration   1: 3.263 ±(99.9%) 0.006 ms/op
Iteration   2: 3.193 ±(99.9%) 0.006 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.184 ±(99.9%) 1.525 ms/op [Average]
  (min, avg, max) = (3.096, 3.184, 3.263), stdev = 0.084
  CI (99.9%): [1.659, 4.709] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.547 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.004 ms/op
Iteration   1: 3.222 ±(99.9%) 0.009 ms/op
Iteration   2: 3.093 ±(99.9%) 0.004 ms/op
Iteration   3: 3.123 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.146 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (3.093, 3.146, 3.222), stdev = 0.068
  CI (99.9%): [1.914, 4.379] (assumes normal distribution)


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
# Warmup Iteration   1: 8.366 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.007 ms/op
Iteration   1: 3.758 ±(99.9%) 0.004 ms/op
Iteration   2: 3.831 ±(99.9%) 0.008 ms/op
Iteration   3: 3.832 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.807 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.758, 3.807, 3.832), stdev = 0.043
  CI (99.9%): [3.031, 4.583] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.299 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.010 ms/op
Iteration   1: 3.191 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  20.054 ms/op
                 createUser·p0.9999: 23.492 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  15.523 ms/op
                 createUser·p0.9999: 23.660 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.278 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  13.489 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297347
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13995 
    [ 2.500,  5.000) = 277221 
    [ 5.000,  7.500) = 5259 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     16.559 ms/op
     p(99.9900) =     23.274 ms/op
     p(99.9990) =     24.479 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 7.218 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.009 ms/op
Iteration   1: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.322 ms/op
                 existUser·p0.999:  10.584 ms/op
                 existUser·p0.9999: 21.142 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 24.125 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   3: 3.245 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  9.773 ms/op
                 existUser·p0.9999: 23.958 ms/op
                 existUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295333
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30978 
    [ 2.500,  5.000) = 256203 
    [ 5.000,  7.500) = 7473 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     23.641 ms/op
     p(99.9990) =     24.791 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 8.109 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.010 ms/op
Iteration   1: 3.325 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   5.256 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  19.182 ms/op
                 getUser·p0.9999: 23.348 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.411 ms/op
                 getUser·p0.999:  10.635 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   3: 3.263 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  10.865 ms/op
                 getUser·p0.9999: 31.196 ms/op
                 getUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294072
  mean =      3.263 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9468 
    [ 2.500,  5.000) = 274176 
    [ 5.000,  7.500) = 9551 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.236 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     29.792 ms/op
     p(99.9990) =     32.606 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 9.577 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.013 ms/op
Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.672 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  17.618 ms/op
                 listUser·p0.9999: 21.963 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.848 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.056 ms/op
                 listUser·p0.9999: 16.663 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251033
  mean =      3.825 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 239877 
    [ 5.000,  7.500) = 9079 
    [ 7.500, 10.000) = 1392 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     15.105 ms/op
     p(99.9900) =     21.198 ms/op
     p(99.9990) =     23.314 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.592 ± 2.273  ops/ms
ClientPb.existUser                       thrpt       3  10.290 ± 2.729  ops/ms
ClientPb.getUser                         thrpt       3   9.862 ± 4.509  ops/ms
ClientPb.listUser                        thrpt       3   8.727 ± 0.853  ops/ms
ClientPb.createUser                       avgt       3   3.180 ± 0.482   ms/op
ClientPb.existUser                        avgt       3   3.184 ± 1.525   ms/op
ClientPb.getUser                          avgt       3   3.146 ± 1.233   ms/op
ClientPb.listUser                         avgt       3   3.807 ± 0.776   ms/op
ClientPb.createUser                     sample  297347   3.225 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.174           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.559           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.274           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.642           ms/op
ClientPb.existUser                      sample  295333   3.246 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.418           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.976           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.641           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.199           ms/op
ClientPb.getUser                        sample  294072   3.263 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.159           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.236           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.008           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.792           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  251033   3.825 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.672           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.105           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.198           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.364           ms/op
