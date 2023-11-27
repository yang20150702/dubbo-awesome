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
# Warmup Iteration   1: 3.053 ops/ms
# Warmup Iteration   2: 9.905 ops/ms
# Warmup Iteration   3: 10.411 ops/ms
Iteration   1: 10.871 ops/ms
Iteration   2: 10.761 ops/ms
Iteration   3: 10.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.855 ±(99.9%) 1.606 ops/ms [Average]
  (min, avg, max) = (10.761, 10.855, 10.935), stdev = 0.088
  CI (99.9%): [9.250, 12.461] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 6.143 ops/ms
# Warmup Iteration   2: 10.766 ops/ms
# Warmup Iteration   3: 11.189 ops/ms
Iteration   1: 11.064 ops/ms
Iteration   2: 11.216 ops/ms
Iteration   3: 11.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  11.197 ±(99.9%) 2.271 ops/ms [Average]
  (min, avg, max) = (11.064, 11.197, 11.311), stdev = 0.124
  CI (99.9%): [8.926, 13.468] (assumes normal distribution)


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
# Warmup Iteration   1: 5.848 ops/ms
# Warmup Iteration   2: 10.772 ops/ms
# Warmup Iteration   3: 10.900 ops/ms
Iteration   1: 10.928 ops/ms
Iteration   2: 11.103 ops/ms
Iteration   3: 10.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.996 ±(99.9%) 1.711 ops/ms [Average]
  (min, avg, max) = (10.928, 10.996, 11.103), stdev = 0.094
  CI (99.9%): [9.285, 12.707] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.090 ops/ms
# Warmup Iteration   2: 8.894 ops/ms
# Warmup Iteration   3: 9.462 ops/ms
Iteration   1: 9.448 ops/ms
Iteration   2: 8.935 ops/ms
Iteration   3: 9.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  9.157 ±(99.9%) 4.799 ops/ms [Average]
  (min, avg, max) = (8.935, 9.157, 9.448), stdev = 0.263
  CI (99.9%): [4.358, 13.956] (assumes normal distribution)


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
# Warmup Iteration   1: 5.226 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
Iteration   2: 2.945 ±(99.9%) 0.005 ms/op
Iteration   3: 2.884 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.927 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (2.884, 2.927, 2.952), stdev = 0.038
  CI (99.9%): [2.238, 3.616] (assumes normal distribution)


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.821 ±(99.9%) 0.005 ms/op
Iteration   1: 2.825 ±(99.9%) 0.006 ms/op
Iteration   2: 2.812 ±(99.9%) 0.005 ms/op
Iteration   3: 2.803 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.813 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.803, 2.813, 2.825), stdev = 0.011
  CI (99.9%): [2.614, 3.012] (assumes normal distribution)


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
# Warmup Iteration   1: 4.884 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.005 ms/op
Iteration   1: 2.825 ±(99.9%) 0.004 ms/op
Iteration   2: 2.825 ±(99.9%) 0.004 ms/op
Iteration   3: 2.814 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.821 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.814, 2.821, 2.825), stdev = 0.007
  CI (99.9%): [2.701, 2.942] (assumes normal distribution)


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
# Warmup Iteration   1: 6.154 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.006 ms/op
Iteration   1: 3.543 ±(99.9%) 0.008 ms/op
Iteration   2: 3.484 ±(99.9%) 0.007 ms/op
Iteration   3: 3.468 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.498 ±(99.9%) 0.720 ms/op [Average]
  (min, avg, max) = (3.468, 3.498, 3.543), stdev = 0.039
  CI (99.9%): [2.778, 4.218] (assumes normal distribution)


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.008 ms/op
Iteration   1: 2.905 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.552 ms/op
                 createUser·p0.9999: 16.712 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 2.903 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  14.023 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   3: 2.934 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.806 ms/op
                 createUser·p0.999:  11.698 ms/op
                 createUser·p0.9999: 15.994 ms/op
                 createUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 329196
  mean =      2.914 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 119481 
    [ 2.500,  3.750) = 194507 
    [ 3.750,  5.000) = 12962 
    [ 5.000,  6.250) = 1616 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 112 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     11.872 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 2.861 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.854 ±(99.9%) 0.007 ms/op
Iteration   1: 2.852 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  8.275 ms/op
                 existUser·p0.9999: 18.311 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   2: 2.858 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  8.716 ms/op
                 existUser·p0.9999: 17.760 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 2.718 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.724 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  9.723 ms/op
                 existUser·p0.9999: 16.093 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 341486
  mean =      2.808 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 141438 
    [ 2.500,  3.750) = 188917 
    [ 3.750,  5.000) = 8888 
    [ 5.000,  6.250) = 1613 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 114 
    [16.250, 17.500) = 87 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.857 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 5.219 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.888 ±(99.9%) 0.007 ms/op
Iteration   1: 2.910 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  15.106 ms/op
                 getUser·p0.9999: 16.450 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 2.940 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  6.654 ms/op
                 getUser·p0.9999: 18.260 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   3: 2.911 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.722 ms/op
                 getUser·p0.99:   4.582 ms/op
                 getUser·p0.999:  8.291 ms/op
                 getUser·p0.9999: 15.499 ms/op
                 getUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 328449
  mean =      2.920 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 119128 
    [ 2.500,  3.750) = 192399 
    [ 3.750,  5.000) = 14680 
    [ 5.000,  6.250) = 1683 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 158 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.465 ms/op
     p(99.9900) =     17.405 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 5.950 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.011 ms/op
Iteration   1: 3.487 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.396 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  11.469 ms/op
                 listUser·p0.9999: 12.943 ms/op
                 listUser·p1.00:   13.435 ms/op

Iteration   2: 3.490 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.412 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  11.663 ms/op
                 listUser·p0.9999: 12.725 ms/op
                 listUser·p1.00:   13.746 ms/op

Iteration   3: 3.531 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.441 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.172 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 273817
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 24905 
    [ 2.500,  3.750) = 160041 
    [ 3.750,  5.000) = 72672 
    [ 5.000,  6.250) = 12334 
    [ 6.250,  7.500) = 2776 
    [ 7.500,  8.750) = 389 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 260 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     12.062 ms/op
     p(99.9900) =     16.103 ms/op
     p(99.9990) =     19.350 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.855 ± 1.606  ops/ms
ClientPb.existUser                       thrpt       3  11.197 ± 2.271  ops/ms
ClientPb.getUser                         thrpt       3  10.996 ± 1.711  ops/ms
ClientPb.listUser                        thrpt       3   9.157 ± 4.799  ops/ms
ClientPb.createUser                       avgt       3   2.927 ± 0.689   ms/op
ClientPb.existUser                        avgt       3   2.813 ± 0.199   ms/op
ClientPb.getUser                          avgt       3   2.821 ± 0.121   ms/op
ClientPb.listUser                         avgt       3   3.498 ± 0.720   ms/op
ClientPb.createUser                     sample  329196   2.914 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.675           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.941           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.551           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.872           ms/op
ClientPb.createUser:createUser·p0.9999  sample          18.088           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.956           ms/op
ClientPb.existUser                      sample  341486   2.808 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.963           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.798           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.857           ms/op
ClientPb.existUser:existUser·p0.9999    sample          17.596           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.235           ms/op
ClientPb.getUser                        sample  328449   2.920 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.800           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.945           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.564           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.465           ms/op
ClientPb.getUser:getUser·p0.9999        sample          17.405           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.842           ms/op
ClientPb.listUser                       sample  273817   3.503 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.029           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.416           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.062           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.103           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.497           ms/op
