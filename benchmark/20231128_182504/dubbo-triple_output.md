# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ops/ms
# Warmup Iteration   2: 12.342 ops/ms
# Warmup Iteration   3: 12.411 ops/ms
Iteration   1: 12.747 ops/ms
Iteration   2: 12.651 ops/ms
Iteration   3: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.771 ±(99.9%) 2.424 ops/ms [Average]
  (min, avg, max) = (12.651, 12.771, 12.914), stdev = 0.133
  CI (99.9%): [10.347, 15.195] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.262 ops/ms
# Warmup Iteration   2: 12.923 ops/ms
# Warmup Iteration   3: 13.017 ops/ms
Iteration   1: 13.114 ops/ms
Iteration   2: 13.155 ops/ms
Iteration   3: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.105 ±(99.9%) 1.003 ops/ms [Average]
  (min, avg, max) = (13.047, 13.105, 13.155), stdev = 0.055
  CI (99.9%): [12.103, 14.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 12.294 ops/ms
# Warmup Iteration   3: 12.552 ops/ms
Iteration   1: 12.773 ops/ms
Iteration   2: 12.700 ops/ms
Iteration   3: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.748 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (12.700, 12.748, 12.773), stdev = 0.042
  CI (99.9%): [11.985, 13.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.817 ops/ms
# Warmup Iteration   2: 10.767 ops/ms
# Warmup Iteration   3: 10.755 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.829 ops/ms
Iteration   3: 10.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.703 ±(99.9%) 1.988 ops/ms [Average]
  (min, avg, max) = (10.636, 10.703, 10.829), stdev = 0.109
  CI (99.9%): [8.715, 12.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.365 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.003 ms/op
Iteration   1: 2.559 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.571 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.545, 2.558, 2.571), stdev = 0.013
  CI (99.9%): [2.328, 2.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
Iteration   3: 2.511 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.518 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (2.496, 2.518, 2.546), stdev = 0.026
  CI (99.9%): [2.042, 2.993] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.003 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.478, 2.486, 2.497), stdev = 0.010
  CI (99.9%): [2.299, 2.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.638 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
Iteration   1: 2.990 ±(99.9%) 0.004 ms/op
Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
Iteration   3: 3.025 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (2.990, 3.007, 3.025), stdev = 0.018
  CI (99.9%): [2.687, 3.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  10.253 ms/op
                 createUser·p0.9999: 14.281 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  9.755 ms/op
                 createUser·p0.9999: 12.472 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  7.481 ms/op
                 createUser·p0.9999: 10.080 ms/op
                 createUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382934
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 184088 
    [ 2.500,  3.750) = 194014 
    [ 3.750,  5.000) = 3795 
    [ 5.000,  6.250) = 516 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      7.685 ms/op
     p(99.9900) =     13.556 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   4.066 ms/op
                 existUser·p0.999:  7.528 ms/op
                 existUser·p0.9999: 13.633 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  7.318 ms/op
                 existUser·p0.9999: 13.059 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  7.429 ms/op
                 existUser·p0.9999: 11.109 ms/op
                 existUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387948
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 190372 
    [ 2.500,  3.750) = 193441 
    [ 3.750,  5.000) = 3258 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      7.435 ms/op
     p(99.9900) =     13.324 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 14.193 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  6.013 ms/op
                 getUser·p0.9999: 11.785 ms/op
                 getUser·p1.00:   12.468 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 12.403 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381264
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 187367 
    [ 2.500,  3.750) = 189415 
    [ 3.750,  5.000) = 3574 
    [ 5.000,  6.250) = 449 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.790 ms/op
     p(99.9900) =     13.752 ms/op
     p(99.9990) =     14.496 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.761 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.009 ms/op
Iteration   1: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.243 ms/op
                 listUser·p0.9999: 11.297 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   2: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  10.043 ms/op
                 listUser·p0.9999: 17.220 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.348 ms/op
                 listUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321282
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 97007 
    [ 2.500,  3.750) = 186675 
    [ 3.750,  5.000) = 30576 
    [ 5.000,  6.250) = 5611 
    [ 6.250,  7.500) = 626 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 177 
    [10.000, 11.250) = 196 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.629 ms/op
     p(99.9900) =     16.132 ms/op
     p(99.9990) =     17.786 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.771 ± 2.424  ops/ms
ClientPb.existUser                       thrpt       3  13.105 ± 1.003  ops/ms
ClientPb.getUser                         thrpt       3  12.748 ± 0.764  ops/ms
ClientPb.listUser                        thrpt       3  10.703 ± 1.988  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.230   ms/op
ClientPb.existUser                        avgt       3   2.518 ± 0.475   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.186   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.320   ms/op
ClientPb.createUser                     sample  382934   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.693           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.685           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.556           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.713           ms/op
ClientPb.existUser                      sample  387948   2.472 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.877           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.435           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.324           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  381264   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.922           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.790           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.752           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  321282   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.785           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.629           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.022           ms/op
