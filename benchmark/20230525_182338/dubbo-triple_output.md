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
# Warmup Iteration   1: 1.966 ops/ms
# Warmup Iteration   2: 5.094 ops/ms
# Warmup Iteration   3: 8.638 ops/ms
Iteration   1: 9.039 ops/ms
Iteration   2: 9.317 ops/ms
Iteration   3: 9.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.158 ±(99.9%) 2.609 ops/ms [Average]
  (min, avg, max) = (9.039, 9.158, 9.317), stdev = 0.143
  CI (99.9%): [6.549, 11.768] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.126 ops/ms
# Warmup Iteration   2: 8.602 ops/ms
# Warmup Iteration   3: 9.365 ops/ms
Iteration   1: 9.256 ops/ms
Iteration   2: 9.511 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.488 ±(99.9%) 4.038 ops/ms [Average]
  (min, avg, max) = (9.256, 9.488, 9.696), stdev = 0.221
  CI (99.9%): [5.449, 13.526] (assumes normal distribution)


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
# Warmup Iteration   1: 2.704 ops/ms
# Warmup Iteration   2: 8.287 ops/ms
# Warmup Iteration   3: 9.048 ops/ms
Iteration   1: 9.304 ops/ms
Iteration   2: 9.124 ops/ms
Iteration   3: 9.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.209 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (9.124, 9.209, 9.304), stdev = 0.091
  CI (99.9%): [7.557, 10.861] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.563 ops/ms
# Warmup Iteration   2: 6.914 ops/ms
# Warmup Iteration   3: 7.810 ops/ms
Iteration   1: 7.717 ops/ms
Iteration   2: 8.030 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.930 ±(99.9%) 3.368 ops/ms [Average]
  (min, avg, max) = (7.717, 7.930, 8.042), stdev = 0.185
  CI (99.9%): [4.561, 11.298] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.032 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.008 ms/op
Iteration   1: 3.545 ±(99.9%) 0.010 ms/op
Iteration   2: 3.385 ±(99.9%) 0.007 ms/op
Iteration   3: 3.467 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.466 ±(99.9%) 1.457 ms/op [Average]
  (min, avg, max) = (3.385, 3.466, 3.545), stdev = 0.080
  CI (99.9%): [2.009, 4.923] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.448 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.007 ms/op
Iteration   1: 3.344 ±(99.9%) 0.005 ms/op
Iteration   2: 3.347 ±(99.9%) 0.007 ms/op
Iteration   3: 3.300 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.330 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.300, 3.330, 3.347), stdev = 0.026
  CI (99.9%): [2.855, 3.806] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.175 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.003 ms/op
Iteration   1: 3.515 ±(99.9%) 0.003 ms/op
Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
Iteration   3: 3.483 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.484 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.454, 3.484, 3.515), stdev = 0.030
  CI (99.9%): [2.931, 4.037] (assumes normal distribution)


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
# Warmup Iteration   1: 12.225 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.011 ms/op
Iteration   1: 4.131 ±(99.9%) 0.013 ms/op
Iteration   2: 4.155 ±(99.9%) 0.006 ms/op
Iteration   3: 3.961 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.082 ±(99.9%) 1.932 ms/op [Average]
  (min, avg, max) = (3.961, 4.082, 4.155), stdev = 0.106
  CI (99.9%): [2.151, 6.014] (assumes normal distribution)


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
# Warmup Iteration   1: 10.869 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.723 ±(99.9%) 0.014 ms/op
Iteration   1: 3.390 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  20.566 ms/op
                 createUser·p0.9999: 30.165 ms/op
                 createUser·p1.00:   31.064 ms/op

Iteration   2: 3.369 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  22.970 ms/op
                 createUser·p0.9999: 26.968 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 3.371 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.641 ms/op
                 createUser·p0.999:  25.542 ms/op
                 createUser·p0.9999: 30.884 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284201
  mean =      3.377 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9486 
    [ 2.500,  5.000) = 270542 
    [ 5.000,  7.500) = 3361 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     20.690 ms/op
     p(99.9900) =     30.624 ms/op
     p(99.9990) =     31.768 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.647 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.009 ms/op
Iteration   1: 3.362 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  22.039 ms/op
                 existUser·p0.9999: 28.128 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.436 ms/op
                 existUser·p0.999:  23.729 ms/op
                 existUser·p0.9999: 26.415 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 3.432 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  25.752 ms/op
                 existUser·p0.9999: 34.275 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281185
  mean =      3.411 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5220 
    [ 2.500,  5.000) = 268961 
    [ 5.000,  7.500) = 5765 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     22.788 ms/op
     p(99.9900) =     32.172 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 10.058 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.011 ms/op
Iteration   1: 3.636 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  22.581 ms/op
                 getUser·p0.9999: 35.193 ms/op
                 getUser·p1.00:   36.766 ms/op

Iteration   2: 3.449 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  24.936 ms/op
                 getUser·p0.9999: 30.966 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   3: 3.465 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.653 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  24.438 ms/op
                 getUser·p0.9999: 32.990 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272862
  mean =      3.515 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7425 
    [ 2.500,  5.000) = 254568 
    [ 5.000,  7.500) = 9254 
    [ 7.500, 10.000) = 1137 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 41 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     33.976 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.635 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.910 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.015 ms/op
Iteration   1: 4.213 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  23.996 ms/op
                 listUser·p0.9999: 25.940 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.821 ms/op
                 listUser·p0.999:  16.567 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 4.007 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.380 ms/op
                 listUser·p0.9999: 21.498 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234573
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 223756 
    [ 5.000,  7.500) = 8253 
    [ 7.500, 10.000) = 1492 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     17.868 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     26.726 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.158 ± 2.609  ops/ms
ClientPb.existUser                       thrpt       3   9.488 ± 4.038  ops/ms
ClientPb.getUser                         thrpt       3   9.209 ± 1.652  ops/ms
ClientPb.listUser                        thrpt       3   7.930 ± 3.368  ops/ms
ClientPb.createUser                       avgt       3   3.466 ± 1.457   ms/op
ClientPb.existUser                        avgt       3   3.330 ± 0.475   ms/op
ClientPb.getUser                          avgt       3   3.484 ± 0.553   ms/op
ClientPb.listUser                         avgt       3   4.082 ± 1.932   ms/op
ClientPb.createUser                     sample  284201   3.377 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.331           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.690           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.624           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.047           ms/op
ClientPb.existUser                      sample  281185   3.411 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.894           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.788           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.172           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.537           ms/op
ClientPb.getUser                        sample  272862   3.515 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.243           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.938           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.766           ms/op
ClientPb.listUser                       sample  234573   4.089 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.868           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.264           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034           ms/op
