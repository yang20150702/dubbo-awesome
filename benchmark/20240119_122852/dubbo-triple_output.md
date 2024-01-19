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
# Warmup Iteration   1: 4.883 ops/ms
# Warmup Iteration   2: 12.596 ops/ms
# Warmup Iteration   3: 12.531 ops/ms
Iteration   1: 12.694 ops/ms
Iteration   2: 12.769 ops/ms
Iteration   3: 13.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.838 ±(99.9%) 3.435 ops/ms [Average]
  (min, avg, max) = (12.694, 12.838, 13.051), stdev = 0.188
  CI (99.9%): [9.403, 16.273] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.526 ops/ms
# Warmup Iteration   2: 12.977 ops/ms
# Warmup Iteration   3: 13.128 ops/ms
Iteration   1: 13.210 ops/ms
Iteration   2: 13.199 ops/ms
Iteration   3: 13.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.174 ±(99.9%) 0.984 ops/ms [Average]
  (min, avg, max) = (13.112, 13.174, 13.210), stdev = 0.054
  CI (99.9%): [12.190, 14.158] (assumes normal distribution)


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
# Warmup Iteration   1: 8.378 ops/ms
# Warmup Iteration   2: 12.809 ops/ms
# Warmup Iteration   3: 13.084 ops/ms
Iteration   1: 13.181 ops/ms
Iteration   2: 13.139 ops/ms
Iteration   3: 13.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.173 ±(99.9%) 0.545 ops/ms [Average]
  (min, avg, max) = (13.139, 13.173, 13.197), stdev = 0.030
  CI (99.9%): [12.627, 13.718] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.856 ops/ms
# Warmup Iteration   2: 10.714 ops/ms
# Warmup Iteration   3: 10.964 ops/ms
Iteration   1: 10.850 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.854 ±(99.9%) 0.787 ops/ms [Average]
  (min, avg, max) = (10.813, 10.854, 10.899), stdev = 0.043
  CI (99.9%): [10.067, 11.641] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.003 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
Iteration   3: 2.413 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.442 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (2.413, 2.442, 2.483), stdev = 0.037
  CI (99.9%): [1.773, 3.112] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.399 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.003 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.420, 2.435, 2.444), stdev = 0.013
  CI (99.9%): [2.204, 2.665] (assumes normal distribution)


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.003 ms/op
Iteration   1: 2.450 ±(99.9%) 0.003 ms/op
Iteration   2: 2.456 ±(99.9%) 0.003 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (2.450, 2.470, 2.502), stdev = 0.028
  CI (99.9%): [1.950, 2.989] (assumes normal distribution)


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
# Warmup Iteration   1: 4.473 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.004 ms/op
Iteration   2: 2.976 ±(99.9%) 0.005 ms/op
Iteration   3: 2.958 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.958, 2.964, 2.976), stdev = 0.010
  CI (99.9%): [2.776, 3.153] (assumes normal distribution)


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  10.496 ms/op
                 createUser·p0.9999: 13.427 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  9.659 ms/op
                 createUser·p0.9999: 11.891 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  8.415 ms/op
                 createUser·p0.9999: 11.100 ms/op
                 createUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383795
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 187394 
    [ 2.500,  3.750) = 192296 
    [ 3.750,  5.000) = 3155 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     13.085 ms/op
     p(99.9990) =     13.683 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  5.902 ms/op
                 existUser·p0.9999: 13.712 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  6.570 ms/op
                 existUser·p0.9999: 12.878 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 12.255 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391446
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 196616 
    [ 2.500,  3.750) = 191553 
    [ 3.750,  5.000) = 2464 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.807 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.047 ms/op
                 getUser·p0.999:  8.485 ms/op
                 getUser·p0.9999: 14.260 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  9.566 ms/op
                 getUser·p0.9999: 12.157 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  6.502 ms/op
                 getUser·p0.9999: 11.296 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385289
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 193875 
    [ 2.500,  3.750) = 184891 
    [ 3.750,  5.000) = 4775 
    [ 5.000,  6.250) = 1138 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.470 ms/op
     p(99.9900) =     13.639 ms/op
     p(99.9990) =     14.662 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.008 ms/op
Iteration   1: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.426 ms/op
                 listUser·p0.999:  8.520 ms/op
                 listUser·p0.9999: 10.619 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 2.942 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.727 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.124 ms/op
                 listUser·p0.9999: 12.405 ms/op
                 listUser·p1.00:   13.173 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.455 ms/op
                 listUser·p0.9999: 11.194 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325167
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 101818 
    [ 2.500,  3.750) = 187429 
    [ 3.750,  5.000) = 29359 
    [ 5.000,  6.250) = 5208 
    [ 6.250,  7.500) = 553 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     11.378 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.838 ± 3.435  ops/ms
ClientPb.existUser                       thrpt       3  13.174 ± 0.984  ops/ms
ClientPb.getUser                         thrpt       3  13.173 ± 0.545  ops/ms
ClientPb.listUser                        thrpt       3  10.854 ± 0.787  ops/ms
ClientPb.createUser                       avgt       3   2.442 ± 0.670   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.230   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.519   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.188   ms/op
ClientPb.createUser                     sample  383795   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.867           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.011           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.085           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.926           ms/op
ClientPb.existUser                      sample  391446   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.792           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.077           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.057           ms/op
ClientPb.getUser                        sample  385289   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.847           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.470           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.639           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.975           ms/op
ClientPb.listUser                       sample  325167   2.951 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.727           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.884           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.995           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.378           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
