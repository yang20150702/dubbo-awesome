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
# Warmup Iteration   1: 5.011 ops/ms
# Warmup Iteration   2: 11.929 ops/ms
# Warmup Iteration   3: 12.310 ops/ms
Iteration   1: 12.486 ops/ms
Iteration   2: 12.469 ops/ms
Iteration   3: 12.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.539 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (12.469, 12.539, 12.661), stdev = 0.107
  CI (99.9%): [10.593, 14.484] (assumes normal distribution)


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
# Warmup Iteration   1: 8.301 ops/ms
# Warmup Iteration   2: 12.932 ops/ms
# Warmup Iteration   3: 13.003 ops/ms
Iteration   1: 12.857 ops/ms
Iteration   2: 12.944 ops/ms
Iteration   3: 13.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.962 ±(99.9%) 2.098 ops/ms [Average]
  (min, avg, max) = (12.857, 12.962, 13.085), stdev = 0.115
  CI (99.9%): [10.864, 15.061] (assumes normal distribution)


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
# Warmup Iteration   1: 8.011 ops/ms
# Warmup Iteration   2: 12.412 ops/ms
# Warmup Iteration   3: 12.674 ops/ms
Iteration   1: 12.667 ops/ms
Iteration   2: 12.692 ops/ms
Iteration   3: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.664 ±(99.9%) 0.523 ops/ms [Average]
  (min, avg, max) = (12.634, 12.664, 12.692), stdev = 0.029
  CI (99.9%): [12.142, 13.187] (assumes normal distribution)


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
# Warmup Iteration   1: 6.360 ops/ms
# Warmup Iteration   2: 10.467 ops/ms
# Warmup Iteration   3: 10.564 ops/ms
Iteration   1: 10.626 ops/ms
Iteration   2: 10.567 ops/ms
Iteration   3: 10.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.595 ±(99.9%) 0.548 ops/ms [Average]
  (min, avg, max) = (10.567, 10.595, 10.626), stdev = 0.030
  CI (99.9%): [10.047, 11.143] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
Iteration   1: 2.583 ±(99.9%) 0.004 ms/op
Iteration   2: 2.593 ±(99.9%) 0.004 ms/op
Iteration   3: 2.569 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.582 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.569, 2.582, 2.593), stdev = 0.012
  CI (99.9%): [2.361, 2.802] (assumes normal distribution)


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.472, 2.478, 2.486), stdev = 0.008
  CI (99.9%): [2.333, 2.622] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (2.490, 2.510, 2.533), stdev = 0.022
  CI (99.9%): [2.116, 2.903] (assumes normal distribution)


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
Iteration   3: 3.023 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.012, 3.025, 3.041), stdev = 0.015
  CI (99.9%): [2.759, 3.291] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.697 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 13.541 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 11.862 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  8.695 ms/op
                 createUser·p0.9999: 17.878 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373560
  mean =      2.567 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 178859 
    [ 2.500,  3.750) = 189795 
    [ 3.750,  5.000) = 3705 
    [ 5.000,  6.250) = 651 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      8.986 ms/op
     p(99.9900) =     13.836 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  5.341 ms/op
                 existUser·p0.9999: 13.839 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.654 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  8.883 ms/op
                 existUser·p0.9999: 13.868 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 11.682 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379204
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 183243 
    [ 2.500,  3.750) = 192843 
    [ 3.750,  5.000) = 2233 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.295 ms/op
     p(99.9900) =     13.715 ms/op
     p(99.9990) =     14.188 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  5.669 ms/op
                 getUser·p0.9999: 13.834 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  9.208 ms/op
                 getUser·p0.9999: 12.165 ms/op
                 getUser·p1.00:   12.681 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  8.554 ms/op
                 getUser·p0.9999: 12.157 ms/op
                 getUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377512
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 185083 
    [ 2.500,  3.750) = 187790 
    [ 3.750,  5.000) = 3584 
    [ 5.000,  6.250) = 537 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      6.647 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     14.061 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.862 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.009 ms/op
Iteration   1: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   11.583 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.014 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.859 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312417
  mean =      3.070 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 106 
    [ 1.250,  2.500) = 83706 
    [ 2.500,  3.750) = 185787 
    [ 3.750,  5.000) = 34685 
    [ 5.000,  6.250) = 6585 
    [ 6.250,  7.500) = 886 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 297 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.244 ms/op
     p(99.9990) =     12.091 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.539 ± 1.945  ops/ms
ClientPb.existUser                       thrpt       3  12.962 ± 2.098  ops/ms
ClientPb.getUser                         thrpt       3  12.664 ± 0.523  ops/ms
ClientPb.listUser                        thrpt       3  10.595 ± 0.548  ops/ms
ClientPb.createUser                       avgt       3   2.582 ± 0.221   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.144   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.394   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.266   ms/op
ClientPb.createUser                     sample  373560   2.567 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.986           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.836           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.940           ms/op
ClientPb.existUser                      sample  379204   2.529 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.729           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.621           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.295           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.715           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.467           ms/op
ClientPb.getUser                        sample  377512   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.715           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.647           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.254           ms/op
ClientPb.listUser                       sample  312417   3.070 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.850           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.244           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.452           ms/op
