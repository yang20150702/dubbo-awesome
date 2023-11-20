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
# Warmup Iteration   1: 4.732 ops/ms
# Warmup Iteration   2: 11.811 ops/ms
# Warmup Iteration   3: 12.045 ops/ms
Iteration   1: 12.209 ops/ms
Iteration   2: 12.348 ops/ms
Iteration   3: 12.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.328 ±(99.9%) 2.017 ops/ms [Average]
  (min, avg, max) = (12.209, 12.328, 12.427), stdev = 0.111
  CI (99.9%): [10.311, 14.346] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 8.050 ops/ms
# Warmup Iteration   2: 12.865 ops/ms
# Warmup Iteration   3: 12.958 ops/ms
Iteration   1: 13.049 ops/ms
Iteration   2: 12.944 ops/ms
Iteration   3: 12.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.953 ±(99.9%) 1.680 ops/ms [Average]
  (min, avg, max) = (12.866, 12.953, 13.049), stdev = 0.092
  CI (99.9%): [11.273, 14.633] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.267 ops/ms
# Warmup Iteration   2: 12.636 ops/ms
# Warmup Iteration   3: 12.680 ops/ms
Iteration   1: 12.697 ops/ms
Iteration   2: 12.649 ops/ms
Iteration   3: 12.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.618 ±(99.9%) 1.798 ops/ms [Average]
  (min, avg, max) = (12.507, 12.618, 12.697), stdev = 0.099
  CI (99.9%): [10.820, 14.415] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.610 ops/ms
# Warmup Iteration   2: 10.343 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.468 ops/ms
Iteration   3: 10.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.508 ±(99.9%) 0.645 ops/ms [Average]
  (min, avg, max) = (10.468, 10.508, 10.533), stdev = 0.035
  CI (99.9%): [9.863, 11.153] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.137 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.003 ms/op
Iteration   2: 2.537 ±(99.9%) 0.003 ms/op
Iteration   3: 2.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.047 ms/op [Average]
  (min, avg, max) = (2.537, 2.540, 2.543), stdev = 0.003
  CI (99.9%): [2.494, 2.587] (assumes normal distribution)


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.003 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (2.433, 2.453, 2.476), stdev = 0.022
  CI (99.9%): [2.053, 2.852] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.518, 2.524, 2.528), stdev = 0.005
  CI (99.9%): [2.428, 2.620] (assumes normal distribution)


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
# Warmup Iteration   1: 4.842 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
Iteration   3: 3.060 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.048 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.041, 3.048, 3.060), stdev = 0.010
  CI (99.9%): [2.859, 3.237] (assumes normal distribution)


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.006 ms/op
Iteration   1: 2.585 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  12.583 ms/op
                 createUser·p0.9999: 14.101 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 13.180 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   3: 2.579 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  9.225 ms/op
                 createUser·p0.9999: 11.888 ms/op
                 createUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372955
  mean =      2.571 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 178203 
    [ 2.500,  3.750) = 189623 
    [ 3.750,  5.000) = 3825 
    [ 5.000,  6.250) = 772 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 127 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      9.274 ms/op
     p(99.9900) =     13.797 ms/op
     p(99.9990) =     14.653 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.736 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 14.664 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  6.112 ms/op
                 existUser·p0.9999: 12.960 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 12.602 ms/op
                 existUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387365
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 189907 
    [ 2.500,  3.750) = 193438 
    [ 3.750,  5.000) = 3133 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      7.156 ms/op
     p(99.9900) =     14.148 ms/op
     p(99.9990) =     14.783 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  11.853 ms/op
                 getUser·p0.9999: 14.041 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  9.169 ms/op
                 getUser·p0.9999: 14.933 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  8.346 ms/op
                 getUser·p0.9999: 12.637 ms/op
                 getUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379113
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 185863 
    [ 2.500,  3.750) = 188255 
    [ 3.750,  5.000) = 3916 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      8.682 ms/op
     p(99.9900) =     14.191 ms/op
     p(99.9990) =     15.739 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.082 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.009 ms/op
Iteration   1: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.281 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  10.433 ms/op
                 listUser·p0.9999: 12.239 ms/op
                 listUser·p1.00:   13.074 ms/op

Iteration   3: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.780 ms/op
                 listUser·p0.9999: 12.190 ms/op
                 listUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315094
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 88409 
    [ 2.500,  3.750) = 184303 
    [ 3.750,  5.000) = 33616 
    [ 5.000,  6.250) = 7105 
    [ 6.250,  7.500) = 838 
    [ 7.500,  8.750) = 172 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 172 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     11.919 ms/op
     p(99.9990) =     12.892 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.328 ± 2.017  ops/ms
ClientPb.existUser                       thrpt       3  12.953 ± 1.680  ops/ms
ClientPb.getUser                         thrpt       3  12.618 ± 1.798  ops/ms
ClientPb.listUser                        thrpt       3  10.508 ± 0.645  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.047   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.399   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.096   ms/op
ClientPb.listUser                         avgt       3   3.048 ± 0.189   ms/op
ClientPb.createUser                     sample  372955   2.571 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.830           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.274           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.797           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  387365   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.022           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.148           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.893           ms/op
ClientPb.getUser                        sample  379113   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.694           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.682           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.191           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.811           ms/op
ClientPb.listUser                       sample  315094   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.891           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.919           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.074           ms/op
