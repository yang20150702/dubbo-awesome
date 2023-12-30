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
# Warmup Iteration   1: 4.774 ops/ms
# Warmup Iteration   2: 11.981 ops/ms
# Warmup Iteration   3: 12.330 ops/ms
Iteration   1: 12.400 ops/ms
Iteration   2: 12.588 ops/ms
Iteration   3: 12.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.521 ±(99.9%) 1.906 ops/ms [Average]
  (min, avg, max) = (12.400, 12.521, 12.588), stdev = 0.104
  CI (99.9%): [10.615, 14.427] (assumes normal distribution)


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
# Warmup Iteration   1: 7.895 ops/ms
# Warmup Iteration   2: 13.065 ops/ms
# Warmup Iteration   3: 13.096 ops/ms
Iteration   1: 13.112 ops/ms
Iteration   2: 12.907 ops/ms
Iteration   3: 12.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.963 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (12.870, 12.963, 13.112), stdev = 0.130
  CI (99.9%): [10.594, 15.332] (assumes normal distribution)


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
# Warmup Iteration   1: 7.595 ops/ms
# Warmup Iteration   2: 12.542 ops/ms
# Warmup Iteration   3: 12.751 ops/ms
Iteration   1: 12.816 ops/ms
Iteration   2: 12.788 ops/ms
Iteration   3: 12.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.785 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (12.752, 12.785, 12.816), stdev = 0.032
  CI (99.9%): [12.202, 13.368] (assumes normal distribution)


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
# Warmup Iteration   1: 6.818 ops/ms
# Warmup Iteration   2: 10.548 ops/ms
# Warmup Iteration   3: 10.569 ops/ms
Iteration   1: 10.654 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.619 ±(99.9%) 0.730 ops/ms [Average]
  (min, avg, max) = (10.575, 10.619, 10.654), stdev = 0.040
  CI (99.9%): [9.889, 11.349] (assumes normal distribution)


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.003 ms/op
Iteration   3: 2.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (2.528, 2.530, 2.533), stdev = 0.003
  CI (99.9%): [2.479, 2.580] (assumes normal distribution)


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.492 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (2.481, 2.492, 2.500), stdev = 0.010
  CI (99.9%): [2.312, 2.671] (assumes normal distribution)


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
# Warmup Iteration   1: 4.093 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.003 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.489, 2.497, 2.508), stdev = 0.010
  CI (99.9%): [2.313, 2.682] (assumes normal distribution)


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
Iteration   3: 3.008 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (3.002, 3.008, 3.013), stdev = 0.006
  CI (99.9%): [2.901, 3.114] (assumes normal distribution)


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  11.173 ms/op
                 createUser·p0.9999: 14.280 ms/op
                 createUser·p1.00:   16.056 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  9.175 ms/op
                 createUser·p0.9999: 11.690 ms/op
                 createUser·p1.00:   12.485 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  8.623 ms/op
                 createUser·p0.9999: 11.196 ms/op
                 createUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380494
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 182807 
    [ 2.500,  3.750) = 194110 
    [ 3.750,  5.000) = 2688 
    [ 5.000,  6.250) = 375 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.823 ms/op
     p(99.9900) =     12.843 ms/op
     p(99.9990) =     14.614 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 3.616 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  5.583 ms/op
                 existUser·p0.9999: 21.379 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  7.810 ms/op
                 existUser·p0.9999: 12.861 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  7.709 ms/op
                 existUser·p0.9999: 11.786 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389543
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191744 
    [ 2.500,  5.000) = 196791 
    [ 5.000,  7.500) = 602 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      7.712 ms/op
     p(99.9900) =     14.205 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  9.097 ms/op
                 getUser·p0.9999: 13.842 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  8.914 ms/op
                 getUser·p0.9999: 12.801 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  6.540 ms/op
                 getUser·p0.9999: 11.012 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385778
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 192229 
    [ 2.500,  3.750) = 188864 
    [ 3.750,  5.000) = 3635 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      7.741 ms/op
     p(99.9900) =     13.360 ms/op
     p(99.9990) =     14.334 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
Iteration   1: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.184 ms/op
                 listUser·p0.9999: 10.909 ms/op
                 listUser·p1.00:   14.811 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.845 ms/op
                 listUser·p0.9999: 12.049 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.740 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 12.638 ms/op
                 listUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317306
  mean =      3.023 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 87552 
    [ 2.500,  3.750) = 190869 
    [ 3.750,  5.000) = 31881 
    [ 5.000,  6.250) = 5684 
    [ 6.250,  7.500) = 582 
    [ 7.500,  8.750) = 154 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     12.047 ms/op
     p(99.9990) =     12.837 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.521 ± 1.906  ops/ms
ClientPb.existUser                       thrpt       3  12.963 ± 2.369  ops/ms
ClientPb.getUser                         thrpt       3  12.785 ± 0.583  ops/ms
ClientPb.listUser                        thrpt       3  10.619 ± 0.730  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.051   ms/op
ClientPb.existUser                        avgt       3   2.492 ± 0.179   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.184   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.107   ms/op
ClientPb.createUser                     sample  380494   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.029           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.823           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.843           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.056           ms/op
ClientPb.existUser                      sample  389543   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.666           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.712           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.205           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.758           ms/op
ClientPb.getUser                        sample  385778   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.741           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.360           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  317306   3.023 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.740           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.047           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.811           ms/op
