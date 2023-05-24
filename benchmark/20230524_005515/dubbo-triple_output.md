# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.963 ops/ms
# Warmup Iteration   2: 5.147 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.871 ops/ms
Iteration   2: 9.430 ops/ms
Iteration   3: 9.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.268 ±(99.9%) 6.304 ops/ms [Average]
  (min, avg, max) = (8.871, 9.268, 9.502), stdev = 0.346
  CI (99.9%): [2.964, 15.572] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.388 ops/ms
# Warmup Iteration   2: 8.966 ops/ms
# Warmup Iteration   3: 9.636 ops/ms
Iteration   1: 9.679 ops/ms
Iteration   2: 9.867 ops/ms
Iteration   3: 9.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.813 ±(99.9%) 2.130 ops/ms [Average]
  (min, avg, max) = (9.679, 9.813, 9.893), stdev = 0.117
  CI (99.9%): [7.683, 11.943] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 8.100 ops/ms
# Warmup Iteration   3: 8.944 ops/ms
Iteration   1: 9.280 ops/ms
Iteration   2: 9.579 ops/ms
Iteration   3: 9.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.413 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (9.280, 9.413, 9.579), stdev = 0.152
  CI (99.9%): [6.636, 12.190] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.448 ops/ms
# Warmup Iteration   2: 6.949 ops/ms
# Warmup Iteration   3: 7.730 ops/ms
Iteration   1: 7.917 ops/ms
Iteration   2: 7.800 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.836 ±(99.9%) 1.280 ops/ms [Average]
  (min, avg, max) = (7.791, 7.836, 7.917), stdev = 0.070
  CI (99.9%): [6.556, 9.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.983 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.006 ms/op
Iteration   1: 3.381 ±(99.9%) 0.014 ms/op
Iteration   2: 3.480 ±(99.9%) 0.007 ms/op
Iteration   3: 3.507 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.456 ±(99.9%) 1.208 ms/op [Average]
  (min, avg, max) = (3.381, 3.456, 3.507), stdev = 0.066
  CI (99.9%): [2.248, 4.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.955 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
Iteration   1: 3.316 ±(99.9%) 0.005 ms/op
Iteration   2: 3.385 ±(99.9%) 0.008 ms/op
Iteration   3: 3.362 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.354 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.316, 3.354, 3.385), stdev = 0.035
  CI (99.9%): [2.713, 3.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.060 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.007 ms/op
Iteration   1: 3.380 ±(99.9%) 0.009 ms/op
Iteration   2: 3.373 ±(99.9%) 0.009 ms/op
Iteration   3: 3.599 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.451 ±(99.9%) 2.347 ms/op [Average]
  (min, avg, max) = (3.373, 3.451, 3.599), stdev = 0.129
  CI (99.9%): [1.104, 5.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.987 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.009 ms/op
Iteration   1: 4.008 ±(99.9%) 0.012 ms/op
Iteration   2: 3.896 ±(99.9%) 0.012 ms/op
Iteration   3: 3.873 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.926 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.873, 3.926, 4.008), stdev = 0.072
  CI (99.9%): [2.615, 5.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.011 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
Iteration   1: 3.399 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  21.515 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.319 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  19.836 ms/op
                 createUser·p0.9999: 25.669 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  22.427 ms/op
                 createUser·p0.9999: 25.683 ms/op
                 createUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282681
  mean =      3.391 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8001 
    [ 2.500,  5.000) = 270335 
    [ 5.000,  7.500) = 3253 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 184 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     21.736 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     26.095 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.558 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.008 ms/op
Iteration   1: 3.281 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.501 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.818 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  11.904 ms/op
                 existUser·p0.9999: 23.479 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   2: 3.366 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  22.812 ms/op
                 existUser·p0.9999: 27.918 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  19.150 ms/op
                 existUser·p0.9999: 28.418 ms/op
                 existUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288211
  mean =      3.328 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8404 
    [ 2.500,  5.000) = 273827 
    [ 5.000,  7.500) = 4887 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     27.897 ms/op
     p(99.9990) =     29.110 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.461 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.010 ms/op
Iteration   1: 3.566 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  20.285 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   2: 3.307 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  12.899 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.443 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  24.045 ms/op
                 getUser·p0.9999: 28.508 ms/op
                 getUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279248
  mean =      3.435 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7238 
    [ 2.500,  5.000) = 264944 
    [ 5.000,  7.500) = 5693 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 137 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     20.505 ms/op
     p(99.9900) =     27.364 ms/op
     p(99.9990) =     28.777 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.490 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.015 ms/op
Iteration   1: 4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.836 ms/op
                 listUser·p0.999:  19.901 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   2: 3.995 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240897
  mean =      3.983 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 232127 
    [ 5.000,  7.500) = 6446 
    [ 7.500, 10.000) = 1343 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      2.081 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     26.076 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.268 ± 6.304  ops/ms
ClientPb.existUser                       thrpt       3   9.813 ± 2.130  ops/ms
ClientPb.getUser                         thrpt       3   9.413 ± 2.777  ops/ms
ClientPb.listUser                        thrpt       3   7.836 ± 1.280  ops/ms
ClientPb.createUser                       avgt       3   3.456 ± 1.208   ms/op
ClientPb.existUser                        avgt       3   3.354 ± 0.641   ms/op
ClientPb.getUser                          avgt       3   3.451 ± 2.347   ms/op
ClientPb.listUser                         avgt       3   3.926 ± 1.310   ms/op
ClientPb.createUser                     sample  282681   3.391 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.736           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.592           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.470           ms/op
ClientPb.existUser                      sample  288211   3.328 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.049           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.915           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.678           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.897           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.262           ms/op
ClientPb.getUser                        sample  279248   3.435 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.505           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.364           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.836           ms/op
ClientPb.listUser                       sample  240897   3.983 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.081           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.373           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.264           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.149           ms/op
