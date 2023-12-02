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
# Warmup Iteration   1: 4.552 ops/ms
# Warmup Iteration   2: 12.003 ops/ms
# Warmup Iteration   3: 12.316 ops/ms
Iteration   1: 12.595 ops/ms
Iteration   2: 12.687 ops/ms
Iteration   3: 12.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.648 ±(99.9%) 0.866 ops/ms [Average]
  (min, avg, max) = (12.595, 12.648, 12.687), stdev = 0.047
  CI (99.9%): [11.782, 13.514] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.162 ops/ms
# Warmup Iteration   2: 13.003 ops/ms
# Warmup Iteration   3: 12.911 ops/ms
Iteration   1: 12.884 ops/ms
Iteration   2: 13.150 ops/ms
Iteration   3: 12.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.996 ±(99.9%) 2.521 ops/ms [Average]
  (min, avg, max) = (12.884, 12.996, 13.150), stdev = 0.138
  CI (99.9%): [10.475, 15.516] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.818 ops/ms
# Warmup Iteration   2: 12.418 ops/ms
# Warmup Iteration   3: 12.744 ops/ms
Iteration   1: 12.855 ops/ms
Iteration   2: 12.611 ops/ms
Iteration   3: 12.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.649 ±(99.9%) 3.475 ops/ms [Average]
  (min, avg, max) = (12.480, 12.649, 12.855), stdev = 0.190
  CI (99.9%): [9.174, 16.123] (assumes normal distribution)


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
# Warmup Iteration   1: 6.743 ops/ms
# Warmup Iteration   2: 10.321 ops/ms
# Warmup Iteration   3: 10.174 ops/ms
Iteration   1: 10.412 ops/ms
Iteration   2: 10.463 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.468 ±(99.9%) 1.091 ops/ms [Average]
  (min, avg, max) = (10.412, 10.468, 10.531), stdev = 0.060
  CI (99.9%): [9.377, 11.560] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.150 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.005 ms/op
Iteration   1: 2.598 ±(99.9%) 0.005 ms/op
Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
Iteration   3: 2.583 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.583 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (2.569, 2.583, 2.598), stdev = 0.014
  CI (99.9%): [2.322, 2.845] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.665 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.003 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.426 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.459 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.426, 2.459, 2.477), stdev = 0.029
  CI (99.9%): [1.937, 2.981] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.817 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.542 ±(99.9%) 0.004 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.535 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.529, 2.535, 2.542), stdev = 0.007
  CI (99.9%): [2.413, 2.657] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.093 ±(99.9%) 0.004 ms/op
Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
Iteration   3: 3.066 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.079 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (3.066, 3.079, 3.093), stdev = 0.014
  CI (99.9%): [2.827, 3.332] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.347 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.724 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.006 ms/op
Iteration   1: 2.587 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  11.583 ms/op
                 createUser·p0.9999: 14.369 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 14.233 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   3: 2.578 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 11.298 ms/op
                 createUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371908
  mean =      2.579 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 178535 
    [ 2.500,  5.000) = 192508 
    [ 5.000,  7.500) = 479 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     14.185 ms/op
     p(99.9990) =     15.340 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  5.594 ms/op
                 existUser·p0.9999: 17.344 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.092 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  9.206 ms/op
                 existUser·p0.9999: 14.752 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.605 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  6.065 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379125
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 185403 
    [ 2.500,  3.750) = 189886 
    [ 3.750,  5.000) = 2816 
    [ 5.000,  6.250) = 611 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      6.157 ms/op
     p(99.9900) =     15.093 ms/op
     p(99.9990) =     17.439 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  11.436 ms/op
                 getUser·p0.9999: 14.439 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  9.145 ms/op
                 getUser·p0.9999: 12.818 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  8.497 ms/op
                 getUser·p0.9999: 12.882 ms/op
                 getUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379618
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 186620 
    [ 2.500,  3.750) = 187816 
    [ 3.750,  5.000) = 4023 
    [ 5.000,  6.250) = 676 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.575 ms/op
     p(99.9900) =     14.091 ms/op
     p(99.9990) =     15.208 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 4.754 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.009 ms/op
Iteration   1: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.187 ms/op
                 listUser·p0.9999: 10.715 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.362 ms/op
                 listUser·p0.9999: 10.664 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.733 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 10.723 ms/op
                 listUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316005
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 88319 
    [ 2.500,  3.750) = 185827 
    [ 3.750,  5.000) = 33543 
    [ 5.000,  6.250) = 6576 
    [ 6.250,  7.500) = 890 
    [ 7.500,  8.750) = 288 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     10.699 ms/op
     p(99.9990) =     11.215 ms/op
     p(99.9999) =     11.452 ms/op
    p(100.0000) =     11.452 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.648 ± 0.866  ops/ms
ClientPb.existUser                       thrpt       3  12.996 ± 2.521  ops/ms
ClientPb.getUser                         thrpt       3  12.649 ± 3.475  ops/ms
ClientPb.listUser                        thrpt       3  10.468 ± 1.091  ops/ms
ClientPb.createUser                       avgt       3   2.583 ± 0.262   ms/op
ClientPb.existUser                        avgt       3   2.459 ± 0.522   ms/op
ClientPb.getUser                          avgt       3   2.535 ± 0.122   ms/op
ClientPb.listUser                         avgt       3   3.079 ± 0.253   ms/op
ClientPb.createUser                     sample  371908   2.579 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.185           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.939           ms/op
ClientPb.existUser                      sample  379125   2.530 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.892           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.157           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.093           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.531           ms/op
ClientPb.getUser                        sample  379618   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.679           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.575           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.091           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.155           ms/op
ClientPb.listUser                       sample  316005   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.733           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.699           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.452           ms/op
