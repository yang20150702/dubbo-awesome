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
# Warmup Iteration   1: 1.563 ops/ms
# Warmup Iteration   2: 3.503 ops/ms
# Warmup Iteration   3: 6.937 ops/ms
Iteration   1: 7.157 ops/ms
Iteration   2: 7.846 ops/ms
Iteration   3: 8.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.674 ±(99.9%) 8.317 ops/ms [Average]
  (min, avg, max) = (7.157, 7.674, 8.019), stdev = 0.456
  CI (99.9%): [≈ 0, 15.991] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.228 ops/ms
# Warmup Iteration   2: 6.729 ops/ms
# Warmup Iteration   3: 8.105 ops/ms
Iteration   1: 8.363 ops/ms
Iteration   2: 8.330 ops/ms
Iteration   3: 8.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.364 ±(99.9%) 0.640 ops/ms [Average]
  (min, avg, max) = (8.330, 8.364, 8.400), stdev = 0.035
  CI (99.9%): [7.724, 9.004] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.131 ops/ms
# Warmup Iteration   2: 6.071 ops/ms
# Warmup Iteration   3: 7.389 ops/ms
Iteration   1: 7.924 ops/ms
Iteration   2: 8.076 ops/ms
Iteration   3: 8.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.001 ±(99.9%) 1.383 ops/ms [Average]
  (min, avg, max) = (7.924, 8.001, 8.076), stdev = 0.076
  CI (99.9%): [6.618, 9.384] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.990 ops/ms
# Warmup Iteration   2: 5.422 ops/ms
# Warmup Iteration   3: 6.610 ops/ms
Iteration   1: 6.285 ops/ms
Iteration   2: 6.612 ops/ms
Iteration   3: 6.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.568 ±(99.9%) 4.821 ops/ms [Average]
  (min, avg, max) = (6.285, 6.568, 6.808), stdev = 0.264
  CI (99.9%): [1.748, 11.389] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.389 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.004 ms/op
Iteration   1: 4.173 ±(99.9%) 0.005 ms/op
Iteration   2: 4.097 ±(99.9%) 0.005 ms/op
Iteration   3: 4.119 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.129 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (4.097, 4.129, 4.173), stdev = 0.039
  CI (99.9%): [3.416, 4.843] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.520 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.004 ms/op
Iteration   1: 3.990 ±(99.9%) 0.002 ms/op
Iteration   2: 3.796 ±(99.9%) 0.004 ms/op
Iteration   3: 3.853 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.879 ±(99.9%) 1.821 ms/op [Average]
  (min, avg, max) = (3.796, 3.879, 3.990), stdev = 0.100
  CI (99.9%): [2.058, 5.701] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.706 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.427 ±(99.9%) 0.007 ms/op
Iteration   1: 4.158 ±(99.9%) 0.004 ms/op
Iteration   2: 3.899 ±(99.9%) 0.008 ms/op
Iteration   3: 3.964 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.007 ±(99.9%) 2.451 ms/op [Average]
  (min, avg, max) = (3.899, 4.007, 4.158), stdev = 0.134
  CI (99.9%): [1.556, 6.458] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.943 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.138 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.771 ±(99.9%) 0.004 ms/op
Iteration   1: 4.746 ±(99.9%) 0.008 ms/op
Iteration   2: 4.634 ±(99.9%) 0.007 ms/op
Iteration   3: 4.816 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.732 ±(99.9%) 1.681 ms/op [Average]
  (min, avg, max) = (4.634, 4.732, 4.816), stdev = 0.092
  CI (99.9%): [3.051, 6.413] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.387 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.409 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.365 ±(99.9%) 0.017 ms/op
Iteration   1: 4.168 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   8.012 ms/op
                 createUser·p0.999:  23.500 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 4.038 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  13.955 ms/op
                 createUser·p0.9999: 27.692 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 4.144 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   8.847 ms/op
                 createUser·p0.999:  28.869 ms/op
                 createUser·p0.9999: 31.598 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233173
  mean =      4.116 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 466 
    [ 2.500,  5.000) = 218571 
    [ 5.000,  7.500) = 11086 
    [ 7.500, 10.000) = 2109 
    [10.000, 12.500) = 541 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     23.614 ms/op
     p(99.9900) =     30.967 ms/op
     p(99.9990) =     32.474 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.182 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.945 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.012 ms/op
Iteration   1: 4.009 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  14.428 ms/op
                 existUser·p0.9999: 30.314 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   2: 3.806 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.690 ms/op
                 existUser·p0.999:  24.412 ms/op
                 existUser·p0.9999: 29.353 ms/op
                 existUser·p1.00:   29.688 ms/op

Iteration   3: 3.917 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   7.868 ms/op
                 existUser·p0.999:  28.228 ms/op
                 existUser·p0.9999: 32.571 ms/op
                 existUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245363
  mean =      3.909 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 516 
    [ 2.500,  5.000) = 233890 
    [ 5.000,  7.500) = 8395 
    [ 7.500, 10.000) = 1778 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     22.115 ms/op
     p(99.9900) =     31.604 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 13.105 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.834 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.016 ms/op
Iteration   1: 4.075 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.034 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  24.084 ms/op
                 getUser·p0.9999: 29.327 ms/op
                 getUser·p1.00:   31.588 ms/op

Iteration   2: 4.089 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.927 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.930 ms/op
                 getUser·p0.999:  14.975 ms/op
                 getUser·p0.9999: 29.115 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   3: 4.024 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   5.247 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  29.054 ms/op
                 getUser·p0.9999: 39.387 ms/op
                 getUser·p1.00:   42.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236210
  mean =      4.063 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 223233 
    [ 5.000, 10.000) = 11972 
    [10.000, 15.000) = 683 
    [15.000, 20.000) = 53 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 141 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     24.176 ms/op
     p(99.9900) =     38.011 ms/op
     p(99.9990) =     39.649 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


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
# Warmup Iteration   1: 14.717 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.998 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.933 ±(99.9%) 0.017 ms/op
Iteration   1: 4.834 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.774 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  25.035 ms/op
                 listUser·p0.9999: 30.209 ms/op
                 listUser·p1.00:   32.113 ms/op

Iteration   2: 4.777 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 23.328 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 4.814 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.654 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  16.435 ms/op
                 listUser·p0.9999: 18.363 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199553
  mean =      4.808 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 164275 
    [ 5.000,  7.500) = 30209 
    [ 7.500, 10.000) = 3576 
    [10.000, 12.500) = 856 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     28.020 ms/op
     p(99.9990) =     32.080 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.674 ± 8.317  ops/ms
ClientPb.existUser                       thrpt       3   8.364 ± 0.640  ops/ms
ClientPb.getUser                         thrpt       3   8.001 ± 1.383  ops/ms
ClientPb.listUser                        thrpt       3   6.568 ± 4.821  ops/ms
ClientPb.createUser                       avgt       3   4.129 ± 0.714   ms/op
ClientPb.existUser                        avgt       3   3.879 ± 1.821   ms/op
ClientPb.getUser                          avgt       3   4.007 ± 2.451   ms/op
ClientPb.listUser                         avgt       3   4.732 ± 1.681   ms/op
ClientPb.createUser                     sample  233173   4.116 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.487           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.614           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.834           ms/op
ClientPb.existUser                      sample  245363   3.909 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.641           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.602           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.115           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.604           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  236210   4.063 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.927           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.086           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.176           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.011           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.861           ms/op
ClientPb.listUser                       sample  199553   4.808 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.890           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.257           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.678           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.020           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.113           ms/op
