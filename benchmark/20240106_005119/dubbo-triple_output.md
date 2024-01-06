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
# Warmup Iteration   1: 4.824 ops/ms
# Warmup Iteration   2: 12.119 ops/ms
# Warmup Iteration   3: 12.439 ops/ms
Iteration   1: 12.583 ops/ms
Iteration   2: 12.686 ops/ms
Iteration   3: 12.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.681 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (12.583, 12.681, 12.774), stdev = 0.096
  CI (99.9%): [10.933, 14.429] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.865 ops/ms
# Warmup Iteration   2: 13.129 ops/ms
# Warmup Iteration   3: 13.202 ops/ms
Iteration   1: 13.247 ops/ms
Iteration   2: 13.262 ops/ms
Iteration   3: 13.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.252 ±(99.9%) 0.164 ops/ms [Average]
  (min, avg, max) = (13.246, 13.252, 13.262), stdev = 0.009
  CI (99.9%): [13.088, 13.415] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.021 ops/ms
# Warmup Iteration   2: 12.628 ops/ms
# Warmup Iteration   3: 12.866 ops/ms
Iteration   1: 12.890 ops/ms
Iteration   2: 12.722 ops/ms
Iteration   3: 12.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.804 ±(99.9%) 1.534 ops/ms [Average]
  (min, avg, max) = (12.722, 12.804, 12.890), stdev = 0.084
  CI (99.9%): [11.270, 14.338] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.804 ops/ms
# Warmup Iteration   2: 10.673 ops/ms
# Warmup Iteration   3: 10.643 ops/ms
Iteration   1: 10.687 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.672 ±(99.9%) 0.471 ops/ms [Average]
  (min, avg, max) = (10.643, 10.672, 10.688), stdev = 0.026
  CI (99.9%): [10.202, 11.143] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.003 ms/op
Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.513 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.499, 2.513, 2.531), stdev = 0.016
  CI (99.9%): [2.215, 2.812] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.660 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.003 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.411 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (2.411, 2.454, 2.503), stdev = 0.046
  CI (99.9%): [1.606, 3.302] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.515 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.519 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (2.500, 2.519, 2.541), stdev = 0.021
  CI (99.9%): [2.137, 2.901] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.650 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.004 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
Iteration   3: 3.041 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (3.015, 3.026, 3.041), stdev = 0.013
  CI (99.9%): [2.782, 3.271] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.590 ±(99.9%) 0.007 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  11.166 ms/op
                 createUser·p0.9999: 13.722 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 12.730 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  8.453 ms/op
                 createUser·p0.9999: 10.275 ms/op
                 createUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383292
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 186332 
    [ 2.500,  3.750) = 193007 
    [ 3.750,  5.000) = 3054 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.510 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.014 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  4.918 ms/op
                 existUser·p0.9999: 14.709 ms/op
                 existUser·p1.00:   15.811 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  7.278 ms/op
                 existUser·p0.9999: 13.337 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 14.271 ms/op
                 existUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391030
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 193631 
    [ 2.500,  3.750) = 194487 
    [ 3.750,  5.000) = 2168 
    [ 5.000,  6.250) = 261 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      8.003 ms/op
     p(99.9900) =     14.054 ms/op
     p(99.9990) =     14.865 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  6.054 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  8.877 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  6.490 ms/op
                 getUser·p0.9999: 10.686 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385331
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 190894 
    [ 2.500,  3.750) = 188176 
    [ 3.750,  5.000) = 4979 
    [ 5.000,  6.250) = 736 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      7.395 ms/op
     p(99.9900) =     13.017 ms/op
     p(99.9990) =     13.863 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.601 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.797 ms/op
                 listUser·p1.00:   11.289 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.112 ms/op
                 listUser·p0.9999: 11.325 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 11.214 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319984
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 90700 
    [ 2.500,  3.750) = 191167 
    [ 3.750,  5.000) = 31487 
    [ 5.000,  6.250) = 5273 
    [ 6.250,  7.500) = 578 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 296 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     10.928 ms/op
     p(99.9990) =     11.679 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.681 ± 1.748  ops/ms
ClientPb.existUser                       thrpt       3  13.252 ± 0.164  ops/ms
ClientPb.getUser                         thrpt       3  12.804 ± 1.534  ops/ms
ClientPb.listUser                        thrpt       3  10.672 ± 0.471  ops/ms
ClientPb.createUser                       avgt       3   2.513 ± 0.298   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.848   ms/op
ClientPb.getUser                          avgt       3   2.519 ± 0.382   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.245   ms/op
ClientPb.createUser                     sample  383292   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.950           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.510           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.123           ms/op
ClientPb.existUser                      sample  391030   2.453 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.720           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.003           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.054           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.811           ms/op
ClientPb.getUser                        sample  385331   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.769           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.395           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.017           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.926           ms/op
ClientPb.listUser                       sample  319984   2.997 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.928           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.550           ms/op
