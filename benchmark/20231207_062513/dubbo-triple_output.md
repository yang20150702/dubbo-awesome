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
# Warmup Iteration   1: 4.773 ops/ms
# Warmup Iteration   2: 12.005 ops/ms
# Warmup Iteration   3: 12.262 ops/ms
Iteration   1: 12.630 ops/ms
Iteration   2: 12.809 ops/ms
Iteration   3: 12.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.753 ±(99.9%) 1.937 ops/ms [Average]
  (min, avg, max) = (12.630, 12.753, 12.819), stdev = 0.106
  CI (99.9%): [10.816, 14.690] (assumes normal distribution)


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
# Warmup Iteration   1: 8.316 ops/ms
# Warmup Iteration   2: 13.000 ops/ms
# Warmup Iteration   3: 12.799 ops/ms
Iteration   1: 12.795 ops/ms
Iteration   2: 12.846 ops/ms
Iteration   3: 12.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.841 ±(99.9%) 0.796 ops/ms [Average]
  (min, avg, max) = (12.795, 12.841, 12.881), stdev = 0.044
  CI (99.9%): [12.045, 13.637] (assumes normal distribution)


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
# Warmup Iteration   1: 7.613 ops/ms
# Warmup Iteration   2: 12.433 ops/ms
# Warmup Iteration   3: 12.604 ops/ms
Iteration   1: 12.698 ops/ms
Iteration   2: 12.616 ops/ms
Iteration   3: 12.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.671 ±(99.9%) 0.861 ops/ms [Average]
  (min, avg, max) = (12.616, 12.671, 12.698), stdev = 0.047
  CI (99.9%): [11.810, 13.532] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.580 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.612 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.570 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (10.412, 10.570, 10.686), stdev = 0.142
  CI (99.9%): [7.988, 13.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.003 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
Iteration   3: 2.518 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.518, 2.533, 2.543), stdev = 0.013
  CI (99.9%): [2.292, 2.773] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.003 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (2.463, 2.468, 2.474), stdev = 0.005
  CI (99.9%): [2.368, 2.568] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.003 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.079 ms/op [Average]
  (min, avg, max) = (2.506, 2.509, 2.514), stdev = 0.004
  CI (99.9%): [2.431, 2.588] (assumes normal distribution)


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
Iteration   3: 2.955 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.955, 2.973, 2.983), stdev = 0.016
  CI (99.9%): [2.686, 3.260] (assumes normal distribution)


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.714 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.591 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  12.149 ms/op
                 createUser·p0.9999: 14.877 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  9.184 ms/op
                 createUser·p0.9999: 15.378 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.067 ms/op
                 createUser·p0.999:  9.175 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375601
  mean =      2.554 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 178219 
    [ 2.500,  3.750) = 192195 
    [ 3.750,  5.000) = 4018 
    [ 5.000,  6.250) = 634 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 82 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     14.828 ms/op
     p(99.9990) =     16.453 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  6.499 ms/op
                 existUser·p0.9999: 14.289 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  7.599 ms/op
                 existUser·p0.9999: 14.513 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  6.437 ms/op
                 existUser·p0.9999: 11.680 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392471
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 193941 
    [ 2.500,  3.750) = 195084 
    [ 3.750,  5.000) = 2496 
    [ 5.000,  6.250) = 476 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.941 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     14.197 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  10.444 ms/op
                 getUser·p0.9999: 22.031 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  9.781 ms/op
                 getUser·p0.9999: 13.198 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 11.456 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383443
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191421 
    [ 2.500,  5.000) = 190953 
    [ 5.000,  7.500) = 669 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      9.226 ms/op
     p(99.9900) =     15.323 ms/op
     p(99.9990) =     22.921 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.009 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.793 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.351 ms/op
                 listUser·p0.9999: 10.443 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  10.027 ms/op
                 listUser·p0.9999: 12.501 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   3: 3.014 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.948 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  10.404 ms/op
                 listUser·p0.9999: 12.933 ms/op
                 listUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318039
  mean =      3.016 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 93881 
    [ 2.500,  3.750) = 183732 
    [ 3.750,  5.000) = 32536 
    [ 5.000,  6.250) = 6225 
    [ 6.250,  7.500) = 800 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     12.485 ms/op
     p(99.9990) =     14.245 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.753 ± 1.937  ops/ms
ClientPb.existUser                       thrpt       3  12.841 ± 0.796  ops/ms
ClientPb.getUser                         thrpt       3  12.671 ± 0.861  ops/ms
ClientPb.listUser                        thrpt       3  10.570 ± 2.582  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.241   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.100   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.079   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.287   ms/op
ClientPb.createUser                     sample  375601   2.554 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.822           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.828           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.744           ms/op
ClientPb.existUser                      sample  392471   2.444 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.941           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.652           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.197           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.614           ms/op
ClientPb.getUser                        sample  383443   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.895           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.226           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.323           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.626           ms/op
ClientPb.listUser                       sample  318039   3.016 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.793           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.485           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.811           ms/op
