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
# Warmup Iteration   1: 1.816 ops/ms
# Warmup Iteration   2: 4.260 ops/ms
# Warmup Iteration   3: 7.105 ops/ms
Iteration   1: 7.343 ops/ms
Iteration   2: 7.859 ops/ms
Iteration   3: 7.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.708 ±(99.9%) 5.801 ops/ms [Average]
  (min, avg, max) = (7.343, 7.708, 7.923), stdev = 0.318
  CI (99.9%): [1.908, 13.509] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.389 ops/ms
# Warmup Iteration   2: 6.761 ops/ms
# Warmup Iteration   3: 8.096 ops/ms
Iteration   1: 8.289 ops/ms
Iteration   2: 8.103 ops/ms
Iteration   3: 8.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.291 ±(99.9%) 3.441 ops/ms [Average]
  (min, avg, max) = (8.103, 8.291, 8.480), stdev = 0.189
  CI (99.9%): [4.850, 11.732] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.512 ops/ms
# Warmup Iteration   2: 7.003 ops/ms
# Warmup Iteration   3: 7.636 ops/ms
Iteration   1: 7.983 ops/ms
Iteration   2: 7.619 ops/ms
Iteration   3: 8.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.900 ±(99.9%) 4.560 ops/ms [Average]
  (min, avg, max) = (7.619, 7.900, 8.097), stdev = 0.250
  CI (99.9%): [3.340, 12.460] (assumes normal distribution)


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
# Warmup Iteration   1: 2.302 ops/ms
# Warmup Iteration   2: 5.438 ops/ms
# Warmup Iteration   3: 6.726 ops/ms
Iteration   1: 6.628 ops/ms
Iteration   2: 7.062 ops/ms
Iteration   3: 6.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.794 ±(99.9%) 4.276 ops/ms [Average]
  (min, avg, max) = (6.628, 6.794, 7.062), stdev = 0.234
  CI (99.9%): [2.518, 11.069] (assumes normal distribution)


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
# Warmup Iteration   1: 15.134 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.394 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.455 ±(99.9%) 0.009 ms/op
Iteration   1: 4.172 ±(99.9%) 0.014 ms/op
Iteration   2: 4.190 ±(99.9%) 0.008 ms/op
Iteration   3: 3.925 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.096 ±(99.9%) 2.699 ms/op [Average]
  (min, avg, max) = (3.925, 4.096, 4.190), stdev = 0.148
  CI (99.9%): [1.397, 6.795] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.639 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.006 ms/op
Iteration   1: 4.074 ±(99.9%) 0.008 ms/op
Iteration   2: 4.257 ±(99.9%) 0.007 ms/op
Iteration   3: 3.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.068 ±(99.9%) 3.503 ms/op [Average]
  (min, avg, max) = (3.874, 4.068, 4.257), stdev = 0.192
  CI (99.9%): [0.566, 7.571] (assumes normal distribution)


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
# Warmup Iteration   1: 12.135 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.475 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.011 ms/op
Iteration   1: 4.257 ±(99.9%) 0.003 ms/op
Iteration   2: 4.080 ±(99.9%) 0.011 ms/op
Iteration   3: 3.986 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.108 ±(99.9%) 2.511 ms/op [Average]
  (min, avg, max) = (3.986, 4.108, 4.257), stdev = 0.138
  CI (99.9%): [1.596, 6.619] (assumes normal distribution)


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
# Warmup Iteration   1: 13.933 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.714 ±(99.9%) 0.016 ms/op
Iteration   1: 4.798 ±(99.9%) 0.013 ms/op
Iteration   2: 4.841 ±(99.9%) 0.008 ms/op
Iteration   3: 4.765 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.802 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (4.765, 4.802, 4.841), stdev = 0.038
  CI (99.9%): [4.106, 5.497] (assumes normal distribution)


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
# Warmup Iteration   1: 13.394 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 5.010 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.317 ±(99.9%) 0.016 ms/op
Iteration   1: 4.118 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.919 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.325 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  23.590 ms/op
                 createUser·p0.9999: 26.474 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 4.306 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.958 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   6.603 ms/op
                 createUser·p0.99:   8.897 ms/op
                 createUser·p0.999:  18.603 ms/op
                 createUser·p0.9999: 28.204 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 4.149 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  29.060 ms/op
                 createUser·p0.9999: 32.909 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229060
  mean =      4.189 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 474 
    [ 2.500,  5.000) = 206897 
    [ 5.000,  7.500) = 17921 
    [ 7.500, 10.000) = 2822 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     23.984 ms/op
     p(99.9900) =     31.803 ms/op
     p(99.9990) =     34.288 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 11.103 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.013 ms/op
Iteration   1: 3.993 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.874 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   6.944 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 25.591 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   2: 3.829 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.005 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  25.966 ms/op
                 existUser·p0.9999: 35.324 ms/op
                 existUser·p1.00:   36.766 ms/op

Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246650
  mean =      3.892 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 460 
    [ 2.500,  5.000) = 236556 
    [ 5.000,  7.500) = 8451 
    [ 7.500, 10.000) = 751 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 51 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     16.144 ms/op
     p(99.9900) =     35.149 ms/op
     p(99.9990) =     35.984 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.704 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.014 ms/op
Iteration   1: 4.010 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  23.867 ms/op
                 getUser·p0.9999: 32.506 ms/op
                 getUser·p1.00:   34.013 ms/op

Iteration   2: 4.079 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  24.707 ms/op
                 getUser·p0.9999: 27.606 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.994 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.042 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  16.480 ms/op
                 getUser·p0.9999: 28.705 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238341
  mean =      4.027 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 222588 
    [ 5.000,  7.500) = 13284 
    [ 7.500, 10.000) = 1691 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 123 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     23.942 ms/op
     p(99.9900) =     30.370 ms/op
     p(99.9990) =     33.628 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 16.209 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.951 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.051 ±(99.9%) 0.018 ms/op
Iteration   1: 4.825 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.217 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  25.813 ms/op
                 listUser·p0.9999: 33.841 ms/op
                 listUser·p1.00:   34.800 ms/op

Iteration   2: 4.956 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   9.734 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 28.380 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   3: 4.905 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.417 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 28.967 ms/op
                 listUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195986
  mean =      4.895 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 146461 
    [ 5.000,  7.500) = 43858 
    [ 7.500, 10.000) = 4103 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     24.642 ms/op
     p(99.9900) =     32.776 ms/op
     p(99.9990) =     34.548 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.708 ± 5.801  ops/ms
ClientPb.existUser                       thrpt       3   8.291 ± 3.441  ops/ms
ClientPb.getUser                         thrpt       3   7.900 ± 4.560  ops/ms
ClientPb.listUser                        thrpt       3   6.794 ± 4.276  ops/ms
ClientPb.createUser                       avgt       3   4.096 ± 2.699   ms/op
ClientPb.existUser                        avgt       3   4.068 ± 3.503   ms/op
ClientPb.getUser                          avgt       3   4.108 ± 2.511   ms/op
ClientPb.listUser                         avgt       3   4.802 ± 0.695   ms/op
ClientPb.createUser                     sample  229060   4.189 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.178           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.964           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.159           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.984           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  246650   3.892 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.225           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.791           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.144           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.149           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.766           ms/op
ClientPb.getUser                        sample  238341   4.027 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.462           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.520           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.942           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.370           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.013           ms/op
ClientPb.listUser                       sample  195986   4.895 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.291           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.454           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.642           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.776           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.800           ms/op
