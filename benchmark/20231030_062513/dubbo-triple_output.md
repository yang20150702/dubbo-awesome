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
# Warmup Iteration   1: 2.715 ops/ms
# Warmup Iteration   2: 6.487 ops/ms
# Warmup Iteration   3: 9.431 ops/ms
Iteration   1: 9.818 ops/ms
Iteration   2: 9.969 ops/ms
Iteration   3: 10.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.969 ±(99.9%) 2.745 ops/ms [Average]
  (min, avg, max) = (9.818, 9.969, 10.119), stdev = 0.150
  CI (99.9%): [7.223, 12.714] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.642 ops/ms
# Warmup Iteration   2: 9.298 ops/ms
# Warmup Iteration   3: 10.187 ops/ms
Iteration   1: 10.359 ops/ms
Iteration   2: 10.372 ops/ms
Iteration   3: 10.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.307 ±(99.9%) 1.870 ops/ms [Average]
  (min, avg, max) = (10.189, 10.307, 10.372), stdev = 0.103
  CI (99.9%): [8.436, 12.177] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ops/ms
# Warmup Iteration   2: 9.349 ops/ms
# Warmup Iteration   3: 9.830 ops/ms
Iteration   1: 9.918 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 10.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.983 ±(99.9%) 1.019 ops/ms [Average]
  (min, avg, max) = (9.918, 9.983, 10.016), stdev = 0.056
  CI (99.9%): [8.963, 11.002] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.522 ops/ms
# Warmup Iteration   2: 7.728 ops/ms
# Warmup Iteration   3: 8.348 ops/ms
Iteration   1: 8.695 ops/ms
Iteration   2: 8.407 ops/ms
Iteration   3: 8.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.536 ±(99.9%) 2.667 ops/ms [Average]
  (min, avg, max) = (8.407, 8.536, 8.695), stdev = 0.146
  CI (99.9%): [5.870, 11.203] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.039 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.004 ms/op
Iteration   1: 3.233 ±(99.9%) 0.004 ms/op
Iteration   2: 3.229 ±(99.9%) 0.006 ms/op
Iteration   3: 3.233 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.232 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (3.229, 3.232, 3.233), stdev = 0.002
  CI (99.9%): [3.191, 3.272] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.052 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.004 ms/op
Iteration   1: 3.126 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.004 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.085 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.062, 3.085, 3.126), stdev = 0.036
  CI (99.9%): [2.421, 3.748] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.939 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.002 ms/op
Iteration   1: 3.265 ±(99.9%) 0.002 ms/op
Iteration   2: 3.229 ±(99.9%) 0.002 ms/op
Iteration   3: 3.317 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.271 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.229, 3.271, 3.317), stdev = 0.044
  CI (99.9%): [2.462, 4.080] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.083 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.006 ms/op
Iteration   1: 3.792 ±(99.9%) 0.004 ms/op
Iteration   2: 3.756 ±(99.9%) 0.005 ms/op
Iteration   3: 3.823 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.791 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (3.756, 3.791, 3.823), stdev = 0.033
  CI (99.9%): [3.181, 4.400] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.400 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.008 ms/op
Iteration   1: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.610 ms/op
                 createUser·p0.999:  18.794 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  16.809 ms/op
                 createUser·p0.9999: 24.119 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   3: 3.287 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  14.975 ms/op
                 createUser·p0.9999: 19.146 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296774
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10825 
    [ 2.500,  5.000) = 281179 
    [ 5.000,  7.500) = 3850 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     16.044 ms/op
     p(99.9900) =     22.686 ms/op
     p(99.9990) =     24.292 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.193 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.342 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 20.598 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 21.918 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 3.106 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  15.286 ms/op
                 existUser·p0.9999: 20.873 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307217
  mean =      3.121 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16070 
    [ 2.500,  5.000) = 286040 
    [ 5.000,  7.500) = 4189 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.213 ms/op
     p(99.9900) =     21.407 ms/op
     p(99.9990) =     22.378 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.331 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.010 ms/op
Iteration   1: 3.336 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.763 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  18.024 ms/op
                 getUser·p0.9999: 36.386 ms/op
                 getUser·p1.00:   37.683 ms/op

Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.985 ms/op
                 getUser·p0.999:  13.988 ms/op
                 getUser·p0.9999: 23.213 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  12.451 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295615
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13247 
    [ 2.500,  5.000) = 274685 
    [ 5.000,  7.500) = 6619 
    [ 7.500, 10.000) = 484 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     14.367 ms/op
     p(99.9900) =     32.905 ms/op
     p(99.9990) =     37.552 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.951 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.011 ms/op
Iteration   1: 3.872 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.957 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 22.057 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 30.735 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   3: 3.772 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.325 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 15.598 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252606
  mean =      3.798 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 246250 
    [ 5.000,  7.500) = 4700 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 302 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     31.356 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.969 ± 2.745  ops/ms
ClientPb.existUser                       thrpt       3  10.307 ± 1.870  ops/ms
ClientPb.getUser                         thrpt       3   9.983 ± 1.019  ops/ms
ClientPb.listUser                        thrpt       3   8.536 ± 2.667  ops/ms
ClientPb.createUser                       avgt       3   3.232 ± 0.041   ms/op
ClientPb.existUser                        avgt       3   3.085 ± 0.663   ms/op
ClientPb.getUser                          avgt       3   3.271 ± 0.809   ms/op
ClientPb.listUser                         avgt       3   3.791 ± 0.609   ms/op
ClientPb.createUser                     sample  296774   3.230 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.956           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.044           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.686           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.035           ms/op
ClientPb.existUser                      sample  307217   3.121 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.765           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.213           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.407           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.774           ms/op
ClientPb.getUser                        sample  295615   3.246 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.905           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.683           ms/op
ClientPb.listUser                       sample  252606   3.798 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.456           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.652           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.910           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.786           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.490           ms/op
