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
# Warmup Iteration   1: 2.728 ops/ms
# Warmup Iteration   2: 6.515 ops/ms
# Warmup Iteration   3: 9.016 ops/ms
Iteration   1: 9.786 ops/ms
Iteration   2: 9.729 ops/ms
Iteration   3: 9.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.695 ±(99.9%) 2.053 ops/ms [Average]
  (min, avg, max) = (9.569, 9.695, 9.786), stdev = 0.113
  CI (99.9%): [7.641, 11.748] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.541 ops/ms
# Warmup Iteration   2: 9.715 ops/ms
# Warmup Iteration   3: 10.260 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.538 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.523 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (10.432, 10.523, 10.600), stdev = 0.085
  CI (99.9%): [8.972, 12.075] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ops/ms
# Warmup Iteration   2: 8.752 ops/ms
# Warmup Iteration   3: 9.985 ops/ms
Iteration   1: 10.294 ops/ms
Iteration   2: 10.147 ops/ms
Iteration   3: 10.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.215 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (10.147, 10.215, 10.294), stdev = 0.074
  CI (99.9%): [8.865, 11.566] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.488 ops/ms
# Warmup Iteration   2: 8.018 ops/ms
# Warmup Iteration   3: 8.664 ops/ms
Iteration   1: 8.592 ops/ms
Iteration   2: 8.464 ops/ms
Iteration   3: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.566 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (8.464, 8.566, 8.641), stdev = 0.092
  CI (99.9%): [6.895, 10.236] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.758 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.005 ms/op
Iteration   1: 3.387 ±(99.9%) 0.008 ms/op
Iteration   2: 3.338 ±(99.9%) 0.007 ms/op
Iteration   3: 3.165 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.297 ±(99.9%) 2.129 ms/op [Average]
  (min, avg, max) = (3.165, 3.297, 3.387), stdev = 0.117
  CI (99.9%): [1.168, 5.426] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.552 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.004 ms/op
Iteration   1: 3.154 ±(99.9%) 0.006 ms/op
Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
Iteration   3: 3.051 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.107 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (3.051, 3.107, 3.154), stdev = 0.052
  CI (99.9%): [2.163, 4.052] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.048 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.002 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
Iteration   3: 3.144 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.147 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.122, 3.147, 3.173), stdev = 0.026
  CI (99.9%): [2.679, 3.615] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.206 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.006 ms/op
Iteration   1: 3.669 ±(99.9%) 0.011 ms/op
Iteration   2: 3.628 ±(99.9%) 0.010 ms/op
Iteration   3: 3.687 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.661 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.628, 3.661, 3.687), stdev = 0.030
  CI (99.9%): [3.107, 4.215] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.723 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.009 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.834 ms/op
                 createUser·p0.999:  12.763 ms/op
                 createUser·p0.9999: 19.299 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  12.648 ms/op
                 createUser·p0.9999: 21.283 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 3.305 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.520 ms/op
                 createUser·p0.999:  14.582 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300035
  mean =      3.203 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26023 
    [ 2.500,  5.000) = 266858 
    [ 5.000,  7.500) = 6411 
    [ 7.500, 10.000) = 328 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.729 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.196 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  12.680 ms/op
                 existUser·p0.9999: 26.509 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  9.998 ms/op
                 existUser·p0.9999: 22.347 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   3: 3.104 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  13.680 ms/op
                 existUser·p0.9999: 24.065 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303359
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21806 
    [ 2.500,  5.000) = 275035 
    [ 5.000,  7.500) = 5519 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     27.295 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 7.781 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.011 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.939 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  18.686 ms/op
                 getUser·p0.9999: 20.576 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   2: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  9.308 ms/op
                 getUser·p0.9999: 21.463 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   3: 3.252 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  10.429 ms/op
                 getUser·p0.9999: 24.057 ms/op
                 getUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295750
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19090 
    [ 2.500,  5.000) = 268195 
    [ 5.000,  7.500) = 7634 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     22.408 ms/op
     p(99.9990) =     24.284 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.320 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.012 ms/op
Iteration   1: 3.860 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 25.320 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 3.724 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 13.730 ms/op
                 listUser·p1.00:   14.483 ms/op

Iteration   3: 3.780 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  13.351 ms/op
                 listUser·p0.9999: 20.402 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253544
  mean =      3.787 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 245321 
    [ 5.000,  7.500) = 6316 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     13.393 ms/op
     p(99.9900) =     22.598 ms/op
     p(99.9990) =     25.541 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.695 ± 2.053  ops/ms
ClientPb.existUser                       thrpt       3  10.523 ± 1.551  ops/ms
ClientPb.getUser                         thrpt       3  10.215 ± 1.351  ops/ms
ClientPb.listUser                        thrpt       3   8.566 ± 1.671  ops/ms
ClientPb.createUser                       avgt       3   3.297 ± 2.129   ms/op
ClientPb.existUser                        avgt       3   3.107 ± 0.945   ms/op
ClientPb.getUser                          avgt       3   3.147 ± 0.468   ms/op
ClientPb.listUser                         avgt       3   3.661 ± 0.554   ms/op
ClientPb.createUser                     sample  300035   3.203 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.644           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.741           ms/op
ClientPb.existUser                      sample  303359   3.163 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.043           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.550           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.461           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.558           ms/op
ClientPb.getUser                        sample  295750   3.248 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.813           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.748           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.408           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.412           ms/op
ClientPb.listUser                       sample  253544   3.787 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.296           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.393           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.598           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
