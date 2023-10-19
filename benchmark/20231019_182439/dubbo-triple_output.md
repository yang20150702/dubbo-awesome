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
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 5.285 ops/ms
# Warmup Iteration   3: 8.428 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.127 ops/ms
Iteration   3: 9.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.232 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (9.127, 9.232, 9.291), stdev = 0.091
  CI (99.9%): [7.576, 10.888] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.920 ops/ms
# Warmup Iteration   2: 8.511 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 9.538 ops/ms
Iteration   2: 9.794 ops/ms
Iteration   3: 9.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.589 ±(99.9%) 3.370 ops/ms [Average]
  (min, avg, max) = (9.435, 9.589, 9.794), stdev = 0.185
  CI (99.9%): [6.219, 12.959] (assumes normal distribution)


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
# Warmup Iteration   1: 2.979 ops/ms
# Warmup Iteration   2: 8.404 ops/ms
# Warmup Iteration   3: 9.217 ops/ms
Iteration   1: 9.161 ops/ms
Iteration   2: 9.298 ops/ms
Iteration   3: 9.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.186 ±(99.9%) 1.851 ops/ms [Average]
  (min, avg, max) = (9.100, 9.186, 9.298), stdev = 0.101
  CI (99.9%): [7.336, 11.037] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.552 ops/ms
# Warmup Iteration   2: 7.024 ops/ms
# Warmup Iteration   3: 7.574 ops/ms
Iteration   1: 7.591 ops/ms
Iteration   2: 7.613 ops/ms
Iteration   3: 7.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.675 ±(99.9%) 2.333 ops/ms [Average]
  (min, avg, max) = (7.591, 7.675, 7.822), stdev = 0.128
  CI (99.9%): [5.342, 10.008] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.248 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.004 ms/op
Iteration   1: 3.457 ±(99.9%) 0.003 ms/op
Iteration   2: 3.453 ±(99.9%) 0.004 ms/op
Iteration   3: 3.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.440 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.410, 3.440, 3.457), stdev = 0.026
  CI (99.9%): [2.967, 3.914] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.793 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.003 ms/op
Iteration   1: 3.277 ±(99.9%) 0.005 ms/op
Iteration   2: 3.292 ±(99.9%) 0.006 ms/op
Iteration   3: 3.321 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.297 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.277, 3.297, 3.321), stdev = 0.022
  CI (99.9%): [2.887, 3.706] (assumes normal distribution)


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
# Warmup Iteration   1: 10.957 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.004 ms/op
Iteration   1: 3.453 ±(99.9%) 0.004 ms/op
Iteration   2: 3.384 ±(99.9%) 0.005 ms/op
Iteration   3: 3.402 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.413 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.384, 3.413, 3.453), stdev = 0.036
  CI (99.9%): [2.760, 4.067] (assumes normal distribution)


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
# Warmup Iteration   1: 12.711 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.006 ms/op
Iteration   1: 4.147 ±(99.9%) 0.007 ms/op
Iteration   2: 4.080 ±(99.9%) 0.008 ms/op
Iteration   3: 4.109 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.112 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (4.080, 4.112, 4.147), stdev = 0.034
  CI (99.9%): [3.498, 4.727] (assumes normal distribution)


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
# Warmup Iteration   1: 10.675 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.014 ms/op
Iteration   1: 3.515 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  21.530 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  23.041 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  20.483 ms/op
                 createUser·p0.9999: 29.688 ms/op
                 createUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275702
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7377 
    [ 2.500,  5.000) = 261819 
    [ 5.000,  7.500) = 5216 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.340 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     28.485 ms/op
     p(99.9990) =     30.392 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.135 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.007 ms/op
Iteration   1: 3.400 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  16.761 ms/op
                 existUser·p0.9999: 19.438 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.457 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.978 ms/op
                 existUser·p0.999:  18.532 ms/op
                 existUser·p0.9999: 22.276 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.436 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  20.115 ms/op
                 existUser·p0.9999: 24.763 ms/op
                 existUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279481
  mean =      3.431 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6675 
    [ 2.500,  5.000) = 266643 
    [ 5.000,  7.500) = 4920 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     17.712 ms/op
     p(99.9900) =     23.496 ms/op
     p(99.9990) =     24.957 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.128 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.011 ms/op
Iteration   1: 3.676 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  22.053 ms/op
                 getUser·p0.9999: 25.077 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   2: 3.544 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  24.729 ms/op
                 getUser·p0.9999: 29.031 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   3: 3.536 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  21.957 ms/op
                 getUser·p0.9999: 28.180 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267716
  mean =      3.584 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1696 
    [ 2.500,  5.000) = 256682 
    [ 5.000,  7.500) = 7371 
    [ 7.500, 10.000) = 1407 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.382 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     28.400 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 12.005 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.506 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.014 ms/op
Iteration   1: 4.190 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.843 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.343 ms/op
                 listUser·p0.999:  21.856 ms/op
                 listUser·p0.9999: 25.698 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   2: 4.197 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 18.995 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.021 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.576 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 17.016 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232071
  mean =      4.134 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 222477 
    [ 5.000,  7.500) = 7596 
    [ 7.500, 10.000) = 1221 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     16.432 ms/op
     p(99.9900) =     24.654 ms/op
     p(99.9990) =     26.521 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.232 ± 1.656  ops/ms
ClientPb.existUser                       thrpt       3   9.589 ± 3.370  ops/ms
ClientPb.getUser                         thrpt       3   9.186 ± 1.851  ops/ms
ClientPb.listUser                        thrpt       3   7.675 ± 2.333  ops/ms
ClientPb.createUser                       avgt       3   3.440 ± 0.473   ms/op
ClientPb.existUser                        avgt       3   3.297 ± 0.409   ms/op
ClientPb.getUser                          avgt       3   3.413 ± 0.654   ms/op
ClientPb.listUser                         avgt       3   4.112 ± 0.614   ms/op
ClientPb.createUser                     sample  275702   3.479 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.374           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.340           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.972           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.485           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.507           ms/op
ClientPb.existUser                      sample  279481   3.431 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.990           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.136           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.712           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.496           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.068           ms/op
ClientPb.getUser                        sample  267716   3.584 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.382           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.334           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.217           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.400           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.474           ms/op
ClientPb.listUser                       sample  232071   4.134 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.432           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.654           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
