# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.561 ops/ms
# Warmup Iteration   2: 3.357 ops/ms
# Warmup Iteration   3: 7.104 ops/ms
Iteration   1: 7.780 ops/ms
Iteration   2: 7.711 ops/ms
Iteration   3: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.789 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (7.711, 7.789, 7.877), stdev = 0.083
  CI (99.9%): [6.271, 9.307] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.261 ops/ms
# Warmup Iteration   2: 5.961 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.314 ops/ms
Iteration   3: 8.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.235 ±(99.9%) 2.773 ops/ms [Average]
  (min, avg, max) = (8.060, 8.235, 8.332), stdev = 0.152
  CI (99.9%): [5.463, 11.008] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.068 ops/ms
# Warmup Iteration   2: 6.399 ops/ms
# Warmup Iteration   3: 7.669 ops/ms
Iteration   1: 7.903 ops/ms
Iteration   2: 8.101 ops/ms
Iteration   3: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.010 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (7.903, 8.010, 8.101), stdev = 0.100
  CI (99.9%): [6.185, 9.835] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.072 ops/ms
# Warmup Iteration   2: 5.845 ops/ms
# Warmup Iteration   3: 6.609 ops/ms
Iteration   1: 6.368 ops/ms
Iteration   2: 6.706 ops/ms
Iteration   3: 6.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.570 ±(99.9%) 3.249 ops/ms [Average]
  (min, avg, max) = (6.368, 6.570, 6.706), stdev = 0.178
  CI (99.9%): [3.320, 9.819] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.041 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.006 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.008 ms/op
Iteration   1: 4.085 ±(99.9%) 0.006 ms/op
Iteration   2: 3.944 ±(99.9%) 0.009 ms/op
Iteration   3: 4.053 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.028 ±(99.9%) 1.353 ms/op [Average]
  (min, avg, max) = (3.944, 4.028, 4.085), stdev = 0.074
  CI (99.9%): [2.675, 5.380] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.551 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.004 ms/op
Iteration   1: 3.775 ±(99.9%) 0.004 ms/op
Iteration   2: 3.867 ±(99.9%) 0.007 ms/op
Iteration   3: 3.853 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.832 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (3.775, 3.832, 3.867), stdev = 0.049
  CI (99.9%): [2.930, 4.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.209 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.009 ms/op
Iteration   1: 4.243 ±(99.9%) 0.009 ms/op
Iteration   2: 3.964 ±(99.9%) 0.007 ms/op
Iteration   3: 3.963 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.057 ±(99.9%) 2.939 ms/op [Average]
  (min, avg, max) = (3.963, 4.057, 4.243), stdev = 0.161
  CI (99.9%): [1.117, 6.996] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.251 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.492 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.878 ±(99.9%) 0.012 ms/op
Iteration   1: 4.834 ±(99.9%) 0.010 ms/op
Iteration   2: 4.838 ±(99.9%) 0.011 ms/op
Iteration   3: 4.714 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.795 ±(99.9%) 1.284 ms/op [Average]
  (min, avg, max) = (4.714, 4.795, 4.838), stdev = 0.070
  CI (99.9%): [3.512, 6.079] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.259 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.726 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.619 ±(99.9%) 0.021 ms/op
Iteration   1: 4.041 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.956 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  21.623 ms/op
                 createUser·p0.9999: 25.175 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.808 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  14.746 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 4.088 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.698 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  24.731 ms/op
                 createUser·p0.9999: 29.032 ms/op
                 createUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237939
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 238 
    [ 2.500,  5.000) = 224005 
    [ 5.000,  7.500) = 11471 
    [ 7.500, 10.000) = 1328 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 96 

  Percentiles, ms/op:
      p(0.0000) =      1.698 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     21.922 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     29.396 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.713 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.013 ms/op
Iteration   1: 3.795 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.937 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   7.381 ms/op
                 existUser·p0.999:  23.399 ms/op
                 existUser·p0.9999: 26.069 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.956 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  11.551 ms/op
                 existUser·p0.9999: 26.471 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 3.968 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.819 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.897 ms/op
                 existUser·p0.999:  14.139 ms/op
                 existUser·p0.9999: 29.945 ms/op
                 existUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245518
  mean =      3.912 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 238 
    [ 2.500,  5.000) = 233205 
    [ 5.000,  7.500) = 9775 
    [ 7.500, 10.000) = 1553 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     29.211 ms/op
     p(99.9990) =     30.983 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.766 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.529 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.013 ms/op
Iteration   1: 4.052 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   6.365 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  23.627 ms/op
                 getUser·p0.9999: 25.507 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.208 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   8.020 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 26.768 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 4.080 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.472 ms/op
                 getUser·p0.999:  26.985 ms/op
                 getUser·p0.9999: 33.574 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238424
  mean =      4.026 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 224127 
    [ 5.000,  7.500) = 9777 
    [ 7.500, 10.000) = 3144 
    [10.000, 12.500) = 873 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     23.546 ms/op
     p(99.9900) =     32.413 ms/op
     p(99.9990) =     34.159 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.734 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 5.795 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.973 ±(99.9%) 0.019 ms/op
Iteration   1: 4.704 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  24.904 ms/op
                 listUser·p0.9999: 27.061 ms/op
                 listUser·p1.00:   29.721 ms/op

Iteration   2: 4.818 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  19.190 ms/op
                 listUser·p0.9999: 25.017 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   3: 4.775 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  17.628 ms/op
                 listUser·p0.9999: 22.288 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201316
  mean =      4.765 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 169321 
    [ 5.000,  7.500) = 26188 
    [ 7.500, 10.000) = 4326 
    [10.000, 12.500) = 844 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     29.500 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.789 ± 1.518  ops/ms
ClientPb.existUser                       thrpt       3   8.235 ± 2.773  ops/ms
ClientPb.getUser                         thrpt       3   8.010 ± 1.825  ops/ms
ClientPb.listUser                        thrpt       3   6.570 ± 3.249  ops/ms
ClientPb.createUser                       avgt       3   4.028 ± 1.353   ms/op
ClientPb.existUser                        avgt       3   3.832 ± 0.901   ms/op
ClientPb.getUser                          avgt       3   4.057 ± 2.939   ms/op
ClientPb.listUser                         avgt       3   4.795 ± 1.284   ms/op
ClientPb.createUser                     sample  237939   4.032 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.698           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.356           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.922           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.819           ms/op
ClientPb.existUser                      sample  245518   3.912 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.819           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.381           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.057           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.211           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.801           ms/op
ClientPb.getUser                        sample  238424   4.026 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.614           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.308           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.684           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.546           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.413           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  201316   4.765 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.085           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.046           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.306           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.103           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.509           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.721           ms/op
