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
# Warmup Iteration   1: 1.718 ops/ms
# Warmup Iteration   2: 4.337 ops/ms
# Warmup Iteration   3: 7.328 ops/ms
Iteration   1: 7.507 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 7.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.789 ±(99.9%) 5.064 ops/ms [Average]
  (min, avg, max) = (7.507, 7.789, 8.062), stdev = 0.278
  CI (99.9%): [2.725, 12.854] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.328 ops/ms
# Warmup Iteration   2: 7.197 ops/ms
# Warmup Iteration   3: 8.300 ops/ms
Iteration   1: 8.273 ops/ms
Iteration   2: 8.131 ops/ms
Iteration   3: 8.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.221 ±(99.9%) 1.426 ops/ms [Average]
  (min, avg, max) = (8.131, 8.221, 8.273), stdev = 0.078
  CI (99.9%): [6.795, 9.648] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.718 ops/ms
# Warmup Iteration   3: 7.746 ops/ms
Iteration   1: 7.689 ops/ms
Iteration   2: 7.817 ops/ms
Iteration   3: 7.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.821 ±(99.9%) 2.435 ops/ms [Average]
  (min, avg, max) = (7.689, 7.821, 7.956), stdev = 0.133
  CI (99.9%): [5.385, 10.256] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.281 ops/ms
# Warmup Iteration   2: 5.857 ops/ms
# Warmup Iteration   3: 6.666 ops/ms
Iteration   1: 6.855 ops/ms
Iteration   2: 6.900 ops/ms
Iteration   3: 6.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.883 ±(99.9%) 0.453 ops/ms [Average]
  (min, avg, max) = (6.855, 6.883, 6.900), stdev = 0.025
  CI (99.9%): [6.430, 7.337] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.080 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.302 ±(99.9%) 0.003 ms/op
Iteration   1: 4.034 ±(99.9%) 0.007 ms/op
Iteration   2: 4.068 ±(99.9%) 0.010 ms/op
Iteration   3: 4.014 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.039 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (4.014, 4.039, 4.068), stdev = 0.028
  CI (99.9%): [3.534, 4.544] (assumes normal distribution)


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
# Warmup Iteration   1: 11.862 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.004 ms/op
Iteration   1: 3.668 ±(99.9%) 0.004 ms/op
Iteration   2: 3.762 ±(99.9%) 0.010 ms/op
Iteration   3: 3.721 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.717 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (3.668, 3.717, 3.762), stdev = 0.047
  CI (99.9%): [2.851, 4.583] (assumes normal distribution)


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
# Warmup Iteration   1: 11.634 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.009 ms/op
Iteration   1: 3.917 ±(99.9%) 0.005 ms/op
Iteration   2: 3.882 ±(99.9%) 0.004 ms/op
Iteration   3: 3.859 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.886 ±(99.9%) 0.537 ms/op [Average]
  (min, avg, max) = (3.859, 3.886, 3.917), stdev = 0.029
  CI (99.9%): [3.349, 4.423] (assumes normal distribution)


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
# Warmup Iteration   1: 14.314 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.413 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.813 ±(99.9%) 0.008 ms/op
Iteration   1: 4.781 ±(99.9%) 0.006 ms/op
Iteration   2: 4.576 ±(99.9%) 0.012 ms/op
Iteration   3: 4.749 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.702 ±(99.9%) 2.013 ms/op [Average]
  (min, avg, max) = (4.576, 4.702, 4.781), stdev = 0.110
  CI (99.9%): [2.689, 6.715] (assumes normal distribution)


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
# Warmup Iteration   1: 12.576 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.620 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.416 ±(99.9%) 0.019 ms/op
Iteration   1: 3.917 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.023 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  12.245 ms/op
                 createUser·p0.9999: 30.223 ms/op
                 createUser·p1.00:   30.966 ms/op

Iteration   2: 4.009 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.382 ms/op
                 createUser·p0.99:   7.954 ms/op
                 createUser·p0.999:  24.124 ms/op
                 createUser·p0.9999: 26.908 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 4.048 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  25.456 ms/op
                 createUser·p0.9999: 37.159 ms/op
                 createUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240491
  mean =      3.991 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 692 
    [ 2.500,  5.000) = 224522 
    [ 5.000,  7.500) = 11978 
    [ 7.500, 10.000) = 2388 
    [10.000, 12.500) = 541 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     23.135 ms/op
     p(99.9900) =     35.835 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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
# Warmup Iteration   1: 12.382 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.013 ms/op
Iteration   1: 3.740 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.409 ms/op
                 existUser·p0.999:  10.378 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 3.859 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   8.234 ms/op
                 existUser·p0.999:  24.936 ms/op
                 existUser·p0.9999: 29.107 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   3: 3.766 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.758 ms/op
                 existUser·p0.999:  13.502 ms/op
                 existUser·p0.9999: 30.132 ms/op
                 existUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253360
  mean =      3.788 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 780 
    [ 2.500,  5.000) = 243351 
    [ 5.000,  7.500) = 6572 
    [ 7.500, 10.000) = 2070 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     13.511 ms/op
     p(99.9900) =     29.557 ms/op
     p(99.9990) =     30.618 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 11.570 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.477 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.016 ms/op
Iteration   1: 3.895 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.894 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.416 ms/op
                 getUser·p0.999:  15.034 ms/op
                 getUser·p0.9999: 30.795 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   2: 3.882 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  24.789 ms/op
                 getUser·p0.9999: 30.138 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   3: 3.960 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.569 ms/op
                 getUser·p0.999:  12.784 ms/op
                 getUser·p0.9999: 31.354 ms/op
                 getUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245304
  mean =      3.912 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 430 
    [ 2.500,  5.000) = 233753 
    [ 5.000,  7.500) = 8843 
    [ 7.500, 10.000) = 1510 
    [10.000, 12.500) = 458 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.282 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     30.833 ms/op
     p(99.9990) =     32.330 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 14.165 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 5.361 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.856 ±(99.9%) 0.021 ms/op
Iteration   1: 4.642 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  26.480 ms/op
                 listUser·p0.9999: 36.525 ms/op
                 listUser·p1.00:   37.945 ms/op

Iteration   2: 4.617 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  18.341 ms/op
                 listUser·p0.9999: 20.768 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.480 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  16.673 ms/op
                 listUser·p0.9999: 18.251 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209502
  mean =      4.578 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 184413 
    [ 5.000,  7.500) = 20275 
    [ 7.500, 10.000) = 3621 
    [10.000, 12.500) = 598 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.450 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     35.983 ms/op
     p(99.9990) =     37.718 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.789 ± 5.064  ops/ms
ClientPb.existUser                       thrpt       3   8.221 ± 1.426  ops/ms
ClientPb.getUser                         thrpt       3   7.821 ± 2.435  ops/ms
ClientPb.listUser                        thrpt       3   6.883 ± 0.453  ops/ms
ClientPb.createUser                       avgt       3   4.039 ± 0.505   ms/op
ClientPb.existUser                        avgt       3   3.717 ± 0.866   ms/op
ClientPb.getUser                          avgt       3   3.886 ± 0.537   ms/op
ClientPb.listUser                         avgt       3   4.702 ± 2.013   ms/op
ClientPb.createUser                     sample  240491   3.991 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.196           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.028           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.135           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.835           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  253360   3.788 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.534           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.604           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.561           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.511           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.557           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.835           ms/op
ClientPb.getUser                        sample  245304   3.912 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.282           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.833           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.440           ms/op
ClientPb.listUser                       sample  209502   4.578 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.450           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.514           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.983           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.945           ms/op
