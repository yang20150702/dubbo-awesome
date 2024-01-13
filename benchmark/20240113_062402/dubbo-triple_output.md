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
# Warmup Iteration   1: 4.889 ops/ms
# Warmup Iteration   2: 11.865 ops/ms
# Warmup Iteration   3: 12.281 ops/ms
Iteration   1: 12.747 ops/ms
Iteration   2: 12.695 ops/ms
Iteration   3: 12.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.714 ±(99.9%) 0.532 ops/ms [Average]
  (min, avg, max) = (12.695, 12.714, 12.747), stdev = 0.029
  CI (99.9%): [12.182, 13.246] (assumes normal distribution)


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
# Warmup Iteration   1: 7.856 ops/ms
# Warmup Iteration   2: 13.039 ops/ms
# Warmup Iteration   3: 12.926 ops/ms
Iteration   1: 12.994 ops/ms
Iteration   2: 12.893 ops/ms
Iteration   3: 12.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.922 ±(99.9%) 1.146 ops/ms [Average]
  (min, avg, max) = (12.878, 12.922, 12.994), stdev = 0.063
  CI (99.9%): [11.776, 14.068] (assumes normal distribution)


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
# Warmup Iteration   1: 7.617 ops/ms
# Warmup Iteration   2: 12.507 ops/ms
# Warmup Iteration   3: 12.738 ops/ms
Iteration   1: 12.633 ops/ms
Iteration   2: 12.794 ops/ms
Iteration   3: 12.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.729 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (12.633, 12.729, 12.794), stdev = 0.085
  CI (99.9%): [11.178, 14.281] (assumes normal distribution)


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
# Warmup Iteration   1: 6.858 ops/ms
# Warmup Iteration   2: 10.406 ops/ms
# Warmup Iteration   3: 10.608 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.653 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.674 ±(99.9%) 0.560 ops/ms [Average]
  (min, avg, max) = (10.653, 10.674, 10.709), stdev = 0.031
  CI (99.9%): [10.114, 11.234] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
Iteration   1: 2.580 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (2.512, 2.542, 2.580), stdev = 0.035
  CI (99.9%): [1.906, 3.178] (assumes normal distribution)


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.462, 2.472, 2.482), stdev = 0.010
  CI (99.9%): [2.287, 2.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.540 ±(99.9%) 0.005 ms/op
Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
Iteration   3: 2.550 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.541 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.532, 2.541, 2.550), stdev = 0.009
  CI (99.9%): [2.371, 2.711] (assumes normal distribution)


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.032 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (3.026, 3.032, 3.036), stdev = 0.005
  CI (99.9%): [2.933, 3.131] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  11.672 ms/op
                 createUser·p0.9999: 13.981 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 12.457 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  8.086 ms/op
                 createUser·p0.9999: 11.407 ms/op
                 createUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380935
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 183627 
    [ 2.500,  3.750) = 193323 
    [ 3.750,  5.000) = 3110 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.111 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.162 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  5.955 ms/op
                 existUser·p0.9999: 15.036 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  6.116 ms/op
                 existUser·p0.9999: 12.942 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  5.788 ms/op
                 existUser·p0.9999: 12.237 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393176
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 195100 
    [ 2.500,  3.750) = 195415 
    [ 3.750,  5.000) = 1967 
    [ 5.000,  6.250) = 272 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      6.003 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     15.756 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  5.447 ms/op
                 getUser·p0.9999: 13.730 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 14.570 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  7.171 ms/op
                 getUser·p0.9999: 11.801 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382907
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 190643 
    [ 2.500,  3.750) = 186777 
    [ 3.750,  5.000) = 4301 
    [ 5.000,  6.250) = 704 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      6.303 ms/op
     p(99.9900) =     13.819 ms/op
     p(99.9990) =     14.978 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 4.763 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.009 ms/op
Iteration   1: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.788 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  10.050 ms/op
                 listUser·p0.9999: 12.632 ms/op
                 listUser·p1.00:   13.451 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.638 ms/op
                 listUser·p0.9999: 11.549 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.718 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  10.142 ms/op
                 listUser·p0.9999: 12.931 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318340
  mean =      3.012 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 90070 
    [ 2.500,  3.750) = 189156 
    [ 3.750,  5.000) = 32627 
    [ 5.000,  6.250) = 5204 
    [ 6.250,  7.500) = 480 
    [ 7.500,  8.750) = 143 
    [ 8.750, 10.000) = 213 
    [10.000, 11.250) = 205 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     12.291 ms/op
     p(99.9990) =     13.399 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.714 ± 0.532  ops/ms
ClientPb.existUser                       thrpt       3  12.922 ± 1.146  ops/ms
ClientPb.getUser                         thrpt       3  12.729 ± 1.551  ops/ms
ClientPb.listUser                        thrpt       3  10.674 ± 0.560  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.636   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.185   ms/op
ClientPb.getUser                          avgt       3   2.541 ± 0.170   ms/op
ClientPb.listUser                         avgt       3   3.032 ± 0.099   ms/op
ClientPb.createUser                     sample  380935   2.517 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.813           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.111           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  393176   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.003           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.615           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.072           ms/op
ClientPb.getUser                        sample  382907   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.613           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.303           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.819           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.024           ms/op
ClientPb.listUser                       sample  318340   3.012 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.718           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.945           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.291           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
